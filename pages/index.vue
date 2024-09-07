<script setup> 
  import DailyLiturgy from '~~/components/DailyLiturgy.vue';
  import SimpleCard from '~~/components/SimpleCard.vue';
</script>

<template>
    <div class="carousel-container">
        <SimpleCard class="simple-card" />
        <DailyLiturgy class="iframe" />
    </div>
</template>

<style scoped>
.carousel-container {
  background-color: rgb(239, 234, 227);
  height: 100%;
}
.simple-card {
    padding-top: 100px;
}
.carousel-data{
    padding-top: 100px;
}
.iframe {
   height: 100vh;
   padding-top: 100px;
}
</style>