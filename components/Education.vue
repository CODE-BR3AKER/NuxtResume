<template>
  <div class="container mx-auto list-container">
    <h3>Education</h3>
    <div class="flex flex-col md:flex-row layout layout-left" v-for="(uni,id) in universities" :key="id">
      <div
        class="pr-4 pl-42 md:w-1/3 pr-4 pl-4 lg:w-1/4 pr-4 pl-4 :flex-growprint-12 details"
      >
        <h4>{{uni.name}}</h4>
        <p><b>{{uni.degree}}</b></p>
        <p>{{uni.period}}</p>
        <p class="no-print aditional-links"></p>
      </div>
      <div
        class="pr-4 pl-42 md:w-2/3 pr-4 pl-4 lg:w-3/4 pr-4 pl-4 :flex-growprint-12 content"
      >
        <p class="quote">
          {{uni.highlight}}
        </p>
        <p>
          {{uni.description}}
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props:['universities']
}
</script>