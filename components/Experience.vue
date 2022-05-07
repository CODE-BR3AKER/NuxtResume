<template>
  <div class="container mx-auto list-container">
    <h3>Experience</h3>
    <div class="flex flex-col md:flex-row layout layout-left" v-for="(job,id) in jobs" :key="id">
      <div
        class="pr-4 pl-42 md:w-1/3 pr-4 pl-4 lg:w-1/4 pr-4 pl-4 :flex-growprint-12 details"
      >
        <h4>{{ job.company }}</h4>
        <p>
          <b>{{ job.title }}</b>
        </p>
        <p>{{ job.period }}</p>
        <a :href="`https://` + job.website" target="_blank" class="link">{{ job.website }}</a>
        <p class="no-print aditional-links"></p>
      </div>
      <div
        class="pr-4 pl-42 md:w-2/3 pr-4 pl-4 lg:w-3/4 pr-4 pl-4 :flex-growprint-12 content"
      >
        <p class="quote">
          {{ job.highlight }}
        </p>
        <p>
          {{ job.description }}
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: ["jobs"],
};
</script>
