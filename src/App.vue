<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data() {
    return {
      links: [
        {
            text: "Home"
        },
        {
            text: "Apple"
        },
        {
            text: "Microsoft"
        },
        {
            text: "Android"
        },
        {
            text: "Forums"
        },
        {
            text: "Contact us"
        },
      ],

      flinks: [
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
    <AppHeader :links="links"/>
    <AppMain/>
    <AppFooter :flinks="flinks"/>
</template>

<style scoped>

</style>
