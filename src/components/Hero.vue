<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
    <div class="hero-container">
        <div class="container">
            <h1>Tech Forum!</h1>
            <p>Discuss all the latest technology news and trends</p>
            <button>GET AVADA NOW!</button>
        </div>
    </div>
</template>

<style scoped>
.hero-container{
    background: url('../img/home_slider_bg.jpg');
    color: white;
}

.container{
    padding-top: 300px;
    padding-left: 300px;
}

h1{
    font-size: 100px;
    margin-bottom: 40px;
}

p{
    font-size: 20px;
    margin-bottom: 50px;
}

button{
    width: 200px;
    background-color: #26a9bd;
    border: none;
    color: white;
    padding: 10px;
    margin-bottom: 330px;
}
</style>