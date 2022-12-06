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

    <div class="card-container">
      <!--CARD-->
      <div class="card">
        <img src="../img/post_feat_img_25-320x202.jpg">
        <strong>Morbi vitae dui euismod vulputate sollicitudin</strong>
        <small>October 11th, 2015 | 2 Comments</small>
        <div class="card-text">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate voluptatibus ipsa, doloremque, repellendus eveniet ipsum sapiente nam illum officia, voluptates deserunt et obcaecati ullam similique? Explicabo eos tenetur blanditiis maxime?</p>
        </div>
      </div>
      <!--/CARD-->

      <!--CARD-->
      <div class="card">
        <img src="../img/post_feat_img_24-320x202.jpg">
        <strong>Morbi vitae dui euismod vulputate sollicitudin</strong>
        <small>October 11th, 2015 | 2 Comments</small>
        <div class="card-text">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate voluptatibus ipsa, doloremque, repellendus eveniet ipsum sapiente nam illum officia, voluptates deserunt et obcaecati ullam similique? Explicabo eos tenetur blanditiis maxime?</p>
        </div>
      </div>
      <!--/CARD-->

      <!--CARD-->
      <div class="card">
        <img src="../img/post_feat_img_23-320x202.jpg">
        <strong>Morbi vitae dui euismod vulputate sollicitudin</strong>
        <small>October 11th, 2015 | 2 Comments</small>
        <div class="card-text">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate voluptatibus ipsa, doloremque, repellendus eveniet ipsum sapiente nam illum officia, voluptates deserunt et obcaecati ullam similique? Explicabo eos tenetur blanditiis maxime?</p>
        </div>
      </div>
      <!--/CARD-->
    </div>
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
  margin: auto;
}

.card-container{
  display: flex;
  justify-content: center;
  margin-top: 50px;
}

strong{
  display: block;

}

img{
  display: block;
}

.card{
  padding: 15px;
}
.card-text{
  width: 300px;
  text-align: left;
}
</style>