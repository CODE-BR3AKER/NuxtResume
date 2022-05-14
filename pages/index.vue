<template>
  <div>
    <Head
      :name="config.name"
      :role="config.title"
      :github="config.social.github"
      :instagram="config.social.instagram"
      :linkedin="config.social.linkedin"
      :twitter="config.social.twitter"
      :youtube="config.social.youtube"
      :mail="config.email"
      :web="config.web"
    />
    <main class="page-content" aria-label="Content">
      <div class="wrapper">
        <About
          :description="about.description"
          :skill_1="about.skill_1"
          :skill_2="about.skill_2"
          :image="about.picture"
        />
        <Projects v-if="config.sections.projects" :projects="projects" />
        <Experience v-if="config.sections.experience" :jobs="experience" />
        <Education v-if="config.sections.education" :universities="education" />
        <Extra v-if="config.sections.extra" :extra="extra" />
      </div>
    </main>
    <Foot :mail="config.email" />
  </div>
</template>

<script>
export default {
  async asyncData({ $content }) {
    const config = await $content("config").fetch();
    const about = await $content("about").fetch();
    const projects = await $content("projects").fetch();
    const experience = await $content("experience").fetch();
    const education = await $content("education").fetch();
    const extra = await $content("extra").fetch();
    return {
      config,
      about,
      projects,
      experience,
      education,
      extra,
    };
  },
  head() {
    return {
      script: [
        { src: "https://identity.netlify.com/v1/netlify-identity-widget.js" },
      ],
    };
  },
  mounted() {
    if (
      window.matchMedia &&
      window.matchMedia("(prefers-color-scheme: dark)").matches
    ) {
      document.body.classList.add("dark");
    }
  },
};
</script>
