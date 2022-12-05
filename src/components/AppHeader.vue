<script>
export default {
  data() {
    return {
      links: [
        {
            text: "Link"
        },
        {
            text: "Link"
        },
        {
            text: "Link"
        },
        {
            text: "Link"
        },
        {
            text: "Link"
        },
        {
            text: "Link"
        },
      ],
    }
  }
}
</script>

<template>
  <div class="header">
    <div class="logo-container">
      <img src="../img/logo.png">
    </div>

    <div class="list-container">
      <ul>
        <li v-for="link in links">
          {{link.text}}
        </li>
        <li>
          <button>JOIN US</button>
        </li>
        <li>
          <i class="fa-solid fa-folder-magnifying-glass"></i>
        </li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
.header{
  background-color: #399bc0;
  display: flex;
  padding: 15px;
  justify-content: space-around;
  align-items: center;
}

ul{
  list-style: none;
  display: flex;
}

li{
  margin-left: 100px;
  color: white;
}
</style>