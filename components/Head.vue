<template>
  <header class="container mx-auto header-contianer">
    <div class="flex flex-col md:flex-row">
      <div
        class="pr-4 pl-42 md:w-1/2 pr-4 pl-4 lg:w-1/2 pr-4 pl-4 xl:w-2/3 pr-4 pl-4 header-left"
      >
        <h1>{{name}}</h1>
        <h2> {{role}}</h2>
      </div>
      <div
        class="pr-4 pl-42 md:w-1/2 pr-4 pl-4 lg:w-1/2 pr-4 pl-4 xl:w-1/3 pr-4 pl-4 header-right"
      >
        <ul class="icons no-print">
          <li>
            <a
              target="_blank"
              :href="github"
              class="button button--sacnite button--round-l"
            >
              <IconGithub/>
            </a>
          </li>
          <li>
            <a
              target="_blank"
              :href="instagram"
              class="button button--sacnite button--round-l"
            >
              <IconInstagram/>
            </a>
          </li>
          <li>
            <a
              target="_blank"
              :href="linkedin"
              class="button button--sacnite button--round-l"
            >
              <IconLinkedin/>
            </a>
          </li>
          <li>
            <a
              target="_blank"
              :href="twitter"
              class="button button--sacnite button--round-l"
            >
              <IconTwitter/>
            </a>
          </li>
          <li>
            <a
              target="_blank"
              :href="youtube"
              class="button button--sacnite button--round-l"
            >
              <IconYoutube/>
            </a>
          </li>
        </ul>
        <p>
          Email:
          <a :href="`mailto:` + mail" target="_blank"
            >{{mail}}</a
          >
        </p>
        <p>
          Web:
          <a
            :href="web"
            target="_blank"
            class=""
            > {{web}}</a
          >
        </p>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  props: {
    name: String,
    role: String,
    github: String,
    instagram: String,
    linkedin: String,
    twitter: String,
    youtube: String,
    mail: String,
    web: String,
  }
}
</script>
