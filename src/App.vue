<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'

export default {
  components: {
    AppHeader,
    AppMain
  },
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
    <AppHeader :links="links"/>
    <AppMain/>
</template>

<style scoped>

</style>
