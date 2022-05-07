<template>
  <div class="container mx-auto list-container">
    <h3>Projects</h3>
    <div class="flex flex-wrap layout layout-top-middle">
      <div
        class="sm:w-1/6 pr-4 pl-42 sm:w-1/3 pr-4 pl-4 md:w-1/4 pr-4 pl-4 :flex-growprint-12 details"
      >
        <h4>{{name}}</h4>
        <a :href="link" target="_blank" class="link"
          >{{link}}</a
        >
        <p class="no-print aditional-links flex justify-center">
          <a
            :href="link"
            target="_blank"
            class="inline"
          >
            <IconGithub class="w-10"/>
          </a>
        </p>
      </div>
      <div
        class="sm:w-1/6 pr-4 pl-42 sm:w-2/3 pr-4 pl-4 md:w-3/4 pr-4 pl-4 :flex-growprint-12 content"
      >
        <p class="quote">
          {{highlight}}
        </p>
        <p>
          {{description}}
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: ['name','link','highlight','description']
}
</script>
