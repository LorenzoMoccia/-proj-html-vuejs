<script>
import Hero from './Hero.vue'

export default {
  components:{
    Hero
  },
}
</script>

<template>
  <Hero/>

  <div class="first-container">
    <h4>AVADA FORUM IS THE PLACE TO BE</h4>

    <div class="text-container">
      <p class="pad">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maxime assumenda eius minus, quaerat dolorem fugit vel soluta officiis praesentium ea exercitationem similique voluptate dolore earum asperiores neque pariatur officia saepe.</p>
    </div>

  </div>

  <div class="news-container">
    <p>PHASELLUS EGET METUS</p>
    <h1>All the latest news</h1>
    <hr>
  </div>
</template>

<style scoped>
.first-container{
  text-align: center;
  background-color: #f2f2f2;
}

.text-container{
  width: 550px;
  margin: auto;
}

h4{
  padding-top: 50px;
}

.pad{
  padding-bottom: 50px;
}

.news-container{
  text-align: center;
}

hr{
  width: 50px;
  color: orange;
}
</style>