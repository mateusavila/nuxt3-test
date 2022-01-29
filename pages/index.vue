<script setup lang="ts">
  import { ref } from 'vue'
  import { Swiper, SwiperSlide } from 'swiper/vue'
  import 'swiper/scss'
  const title = ref<string>('mateus')
</script>
<template>
  <div>
    <h1>{{title}}</h1>
    <swiper
      :slides-per-view="1"
      :space-between="50"
    >
      <swiper-slide>Slide 1</swiper-slide>
      <swiper-slide>Slide 2</swiper-slide>
      <swiper-slide>Slide 3</swiper-slide>
    </swiper>
  </div>
</template>

<style lang="sass">
  h1
    font-family: 'Tahoma', sans-serif
    
</style>