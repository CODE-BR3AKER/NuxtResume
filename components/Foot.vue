<template>
  <footer class="container mx-auto footer-container">
    <p>
      <a :href="`mailto:` + mail" target="_blank">{{ mail }}</a
      >&nbsp;- References on request
    </p>
  </footer>
</template>
<script>
export default {
  props: ["mail"],
};
</script>
