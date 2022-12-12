<script>
export default {
  props: {
    flinks: Array
  }
}
</script>

<template>
  <div class="footer-container">
    <div class="container">
      <!--COLONNA LIST-->
      <div class="list-container">
        <h3>AVADA TECH FORUM</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. A ipsum ex at eaque, velit aut cumque perferendis laboriosam totam pariatur quia harum, dicta sunt hic consequuntur corrupti. Doloribus, dolore pariatur?</p>
      </div>
      <!--/COLONNA LIST-->

      <!--COLONNA LIST-->
      <div class="list-container">
        <ul>
          <li><h3>POPULAR TOPICS</h3></li>
          <li class="border" v-for="link in flinks">
            >{{link.text}}
          </li>
        </ul>
      </div>
      <!--/COLONNA LIST-->

      <!--COLONNA LIST-->
      <div class="list-container">
        <ul>
          <li><h3>RECENT TOPICS</h3></li>
          <li class="border" v-for="link in flinks">
            >{{link.text}}
          </li>
        </ul>
      </div>
      <!--/COLONNA LIST-->

      <!--COLONNA LIST-->
      <div class="list-container">
        <ul>
          <li><h3>LATEST REPLIES</h3></li>
          <li class="border" v-for="link in flinks">
            >{{link.text}}
          </li>
        </ul>
      </div>
      <!--/COLONNA LIST-->
    </div>
  </div>
</template>

<style scoped>


.container{
  display: flex;  
  justify-content: center;
  padding-top: 100px;
  padding-bottom: 100px;
}
.list-container{
  width: 300px;
}

ul{
  list-style: none;
  margin-left: 70px;
}

.border{
  border-top: 1px solid #f2f2f2;
  border-bottom: 1px solid #f2f2f2;
}
</style>