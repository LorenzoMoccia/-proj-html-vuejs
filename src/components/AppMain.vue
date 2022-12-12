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

    <!--CARD CONTAINER-->
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
    <!--/CARD CONTAINER-->

    <!--FEATURED ARTICLE CONTAINER-->
    <div class="featured-article-container">
      <div class="featured-article-text">
        <strong>FEATURED ARTICLE</strong>
        <h2>Cras malesuada et orci eget pharetra</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero iusto aut molestias quaerat temporibus repellendus labore qui tempore, laboriosam perferendis illum quod explicabo voluptatibus voluptates, est minima sed obcaecati expedita.</p>
        <button>READ MORE ></button>
      </div>
    </div>
    <!--/FEATURED ARTICLE CONTAINER-->

    <!--CARD CONTAINER-->
    <div class="card-container">
      <!--CARD-->
      <div class="card">
        <img src="../img/post_feat_img_22-320x202.jpg">
        <strong>Morbi vitae dui euismod vulputate sollicitudin</strong>
        <small>October 11th, 2015 | 2 Comments</small>
        <div class="card-text">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate voluptatibus ipsa, doloremque, repellendus eveniet ipsum sapiente nam illum officia, voluptates deserunt et obcaecati ullam similique? Explicabo eos tenetur blanditiis maxime?</p>
        </div>
      </div>
      <!--/CARD-->

      <!--CARD-->
      <div class="card">
        <img src="../img/post_feat_img_21-320x202.jpg">
        <strong>Morbi vitae dui euismod vulputate sollicitudin</strong>
        <small>October 11th, 2015 | 2 Comments</small>
        <div class="card-text">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate voluptatibus ipsa, doloremque, repellendus eveniet ipsum sapiente nam illum officia, voluptates deserunt et obcaecati ullam similique? Explicabo eos tenetur blanditiis maxime?</p>
        </div>
      </div>
      <!--/CARD-->

      <!--CARD-->
      <div class="card">
        <img src="../img/post_feat_img_20-320x202.jpg">
        <strong>Morbi vitae dui euismod vulputate sollicitudin</strong>
        <small>October 11th, 2015 | 2 Comments</small>
        <div class="card-text">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate voluptatibus ipsa, doloremque, repellendus eveniet ipsum sapiente nam illum officia, voluptates deserunt et obcaecati ullam similique? Explicabo eos tenetur blanditiis maxime?</p>
        </div>
      </div>
      <!--/CARD-->
    </div>
    <!--/CARD CONTAINER-->

    <!--TUTORIAL & GUIDES CONTAINER-->
    <div class="tutorial-container">
      <!--REVIEWED PRODUCT-->
      <div class="reviewed-product">
        <div class="reviewed-product-text">
          <strong>REVIEWED PRODUCT</strong>
          <h2>Mauris viverra atisan ipsum eget felis prims efficitur varius</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, ullam commodi? Corrupti accusamus quam quaerat, voluptas cupiditate assumenda fugit veniam quidem iusto, eveniet veritatis, repellendus illo minus tenetur! Dolor, itaque?</p>
          <button>READ MORE ></button>
        </div>
      </div>
      <!--/REVIEWED PRODUCT-->

      <div class="tutorial-guides">
        <h2>Tutorials & Guides</h2>
        <hr>
        <!--SMALL CARD-->
        <div class="small-card">
          <img src="../img/post_feat_img_23-147x118.jpg" alt="">
          <div class="tutorial-text-container">
            <strong>Donec ornare pretium<br> eget scelisque justo</strong>
            <small>October 11th, 2015 | 2 Comments</small>
          </div>
        </div>
        <!--/SMALL CARD-->

        <!--SMALL CARD-->
        <div class="small-card">
          <img src="../img/post_feat_img_23-147x118.jpg" alt="">
          <div class="tutorial-text-container">
            <strong>Donec ornare pretium<br> eget scelisque justo</strong>
            <small>October 11th, 2015 | 2 Comments</small>
          </div>
        </div>
        <!--/SMALL CARD-->

        <!--SMALL CARD-->
        <div class="small-card">
          <img src="../img/post_feat_img_23-147x118.jpg" alt="">
          <div class="tutorial-text-container">
            <strong>Donec ornare pretium<br> eget scelisque justo</strong>
            <small>October 11th, 2015 | 2 Comments</small>
          </div>
        </div>
        <!--/SMALL CARD-->
      </div>

    </div>
    <!--/TUTORIAL & GUIDES CONTAINER-->

    <!--BLACK ROW-->
    <div class="black-row">
      <h5>READ OUR BLOG</h5>
    </div>
    <!--/BLACK ROW-->

    
    <!--SECTION CONTAINER-->
    <div class="forum-sections-container">
      <p>PHASELLUS EGET METUS</p>
      <h1>Forum Sections</h1>
      <hr>
      <!--FIRST ROW-->
      <div class="row">
        <!--SECTION CARD-->
        <div class="section-card">
          <div class="circle">
            <i class="fa-sharp fa-solid fa-newspaper fa-3x"></i>
          </div>
          <h3 class="section-title">News & Community</h3>
        </div>
        <!--/SECTION CARD-->

        <!--SECTION CARD-->
        <div class="section-card">
          <div class="circle">
            <i class="fa-brands fa-apple fa-3x"></i>
          </div>
          <h3 class="section-title">Apple Forum</h3>
        </div>
        <!--/SECTION CARD-->

        <!--SECTION CARD-->
        <div class="section-card">
          <div class="circle">
            <i class="fa-brands fa-windows fa-3x"></i>
          </div>
          <h3 class="section-title">Microsoft Forum</h3>
        </div>
        <!--/SECTION CARD-->

        <!--SECTION CARD-->
        <div class="section-card">
          <div class="circle">
            <i class="fa-brands fa-android fa-3x"></i>
          </div>
          <h3 class="section-title">Android Forum</h3>
        </div>
        <!--/SECTION CARD-->
      </div>
      <!--/FIRST ROW-->

      <!--SECOND ROW-->
      <div class="row row2">
        <!--SECTION CARD-->
        <div class="section-card">
          <div class="circle">
            <i class="fa-solid fa-mug-saucer fa-3x"></i>
          </div>
          <h3 class="section-title">General Discussion</h3>
        </div>
        <!--/SECTION CARD-->

        <!--SECTION CARD-->
        <div class="section-card">
          <div class="circle">
            <i class="fa-solid fa-code fa-3x"></i>
          </div>
          <h3 class="section-title">App & Software</h3>
        </div>
        <!--/SECTION CARD-->

        <!--SECTION CARD-->
        <div class="section-card">
          <div class="circle">
            <i class="fa-solid fa-laptop fa-3x"></i>
          </div>
          <h3 class="section-title">Gadget & Stuff</h3>
        </div>
        <!--/SECTION CARD-->

        <!--SECTION CARD-->
        <div class="section-card">
          <div class="circle">
            <i class="fa-solid fa-wrench fa-3x"></i>
          </div>
          <h3 class="section-title">Tutorial & Guides</h3>
        </div>
        <!--/SECTION CARD-->
      </div>
      <!--/SECOND ROW-->
    </div>
    <!--/SECTION CONTAINER-->

    <!--BLACK ROW-->
    <div class="black-row">
      <h5>GO TO OUR FORUM</h5>
    </div>
    <!--/BLACK ROW-->

    <!--JOIN TO OUR COMMUNITY-->
    <div class="community-container">
      <div class="community-text-container">
        <h1 class="community-text">Hey! Join to our Community</h1>
        <p class="community-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo, totam sed! Quae dignissimos maxime blanditiis repellat sapiente quos deserunt praesentium magnam, neque recusandae ex possimus aspernatur fuga, atque modi similique?</p>
        <button class="signup-btn">SIGN UP</button>
      </div>
    </div>
    <!--/JOIN TO OUR COMMUNITY-->

    <!--NEWSLETTER-->
    <div class="newsletter-container">
      <h2 class="newsletter-text">Subscribe to our Newsletter</h2>
      <div class="newsletter">
        <input type="text" placeholder="Insert your email" class="newsletter-input">
        <button class="send-btn">SEND</button>
      </div>
    </div>
    <!--/NEWSLETTER-->
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
  padding-top: 50px;
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

.featured-article-container{
  background: url('../img/featured_article_1_bg.jpg');
  background-size: cover;
  width: 55%;
  height: 500px;
  margin: auto;
  margin-top: 100px;
}

.featured-article-text{
  color: white;
  text-align: left;
  padding-top: 200px;
  padding-left: 50px;
}

button{
  padding: 10px;
  background-color: black;
  border: none;
  color: white;
  margin-top: 40px;
}

.tutorial-container{
  display: flex;
  justify-content: center;
  margin-top: 50px;
  padding-bottom: 70px;
}
.reviewed-product{
  background: url('../img/featured_article_2_bg.jpg');
  background-size: contain;
  width: 35%;
  height: 414px;
}

.reviewed-product-text{
  color: white;
  text-align: left;
  padding-top: 70px;
  padding-left: 30px;
}

.small-card{
  display: flex;
  padding-top: 10px;
  padding-left: 30px;
}

.black-row{
  color: white;
  background-color: black;
  padding: 50px;
}

.forum-sections-container{
  background-color: #f2f2f2;
  padding-top: 50px;
}
.section-card{
  width: 200px;
  height: 200px;
  border-top: 4px solid #27afc3;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-left: 50px;
  background-color: white;
  flex-direction: column;
}

.circle{
  width: 85px;
  height: 85px;
  border-radius: 50%;
  background-color: #ff8d61;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 5px;
}

i{
  color: white;
}
.row{
  display: flex;
  justify-content: center;
  margin-top: 100px;
}

.row2{
  padding-bottom: 200px;
}
.community-container{
  background: url('../img/join_now_cta_bg.jpg');
  height: 500px;
}
.community-text{
  color: white;
}

.signup-btn{
  background-color: #26a9bd;
  padding: 10px;
}

.community-text-container{
  padding-top: 200px;
}

.newsletter-container{
  background-color: #f2f2f2;
}

.newsletter-input{
  margin-right: 50px;
  width: 300px;
  margin-bottom: 100px;
}

.send-btn{
  width: 100px;
}

.newsletter-text{
  padding-top: 80px;
}


</style>