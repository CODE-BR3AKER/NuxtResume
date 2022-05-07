<template>
  <div class="container mx-auto text-container">
    <h3>A Little More About Me</h3>
    <div class="flex flex-wrap">
      <div class="pr-4 pl-42">
        <nuxt-content :document="extra"></nuxt-content>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: ["extra"],
};
</script>
