<template>
 <AppTitle />
 <AppHero />
 <AppMain />
</template>

<script>
  import AppTitle from './components/AppTitle.vue'
  import AppHero from './components/AppHero.vue';
  import AppMain from './components/AppMain.vue';
  export default {

    data() {
        return {};
    },
    methods: {},
    components: { AppTitle, AppHero, AppMain }
}
</script>

<style lang="css">
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>