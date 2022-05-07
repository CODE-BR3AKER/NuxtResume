<template>
  <div class="container mx-auto list-container">
    <h3>Experience</h3>
    <div class="flex flex-col md:flex-row layout layout-left">
      <div
        class="pr-4 pl-42 md:w-1/3 pr-4 pl-4 lg:w-1/4 pr-4 pl-4 :flex-growprint-12 details"
      >
        <h4>{{ company }}</h4>
        <p>
          <b>{{ title }}</b>
        </p>
        <p>{{ period }}</p>
        <a :href="`https://` + website" target="_blank" class="link">{{ website }}</a>
        <p class="no-print aditional-links"></p>
      </div>
      <div
        class="pr-4 pl-42 md:w-2/3 pr-4 pl-4 lg:w-3/4 pr-4 pl-4 :flex-growprint-12 content"
      >
        <p class="quote">
          {{ highlight }}
        </p>
        <p>
          {{ description }}
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: ["company", "title", "period", "website", "highlight", "description"],
};
</script>
