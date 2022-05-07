<template>
  <div class="container mx-auto intro-container">
    <h3>About Me</h3>
    <div class="flex flex-col md:flex-row">
      <div class="pr-4 pl-42 md:w-1/3 pr-4 pl-4 lg:w-1/4 pr-4 pl-4 no-print">
        <span
          class="profile-img"
          :style="{ 'background-image': 'url(' + image + ')' }"
        ></span>
      </div>
      <div
        class="pr-4 pl-42 md:w-2/3 pr-4 pl-4 lg:w-3/4 pr-4 pl-4 :flex-growprint-12"
      >
        <p>
          {{description}}
        </p>
        <p>
          I am most skilled in: <mark>{{skill_1}}</mark> and
          <mark>{{skill_2}}</mark>.
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props:['description','skill_1','skill_2','image']
}
</script>
