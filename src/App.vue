<script>
// 1. importo il componente dai component
import AppHeader from './components/AppHeader.vue'; // let AppHeader = quelloCheTroviDentro(AppHeader)
import AppMain from './components/AppMain.vue';

export default {
  data() {
    return {
      count: 0
    }
  },
  components: {
    // 2. lo importo nella listab dei componenti del mio componente
  AppHeader,
  AppMain,
},
  methods: {},
  computed: {},
  mounted() {},
}
</script>

<template>
   <!-- 3. inserisco il mio componente dove voglio sia visibile -->
  <AppHeader />
  <AppMain />
</template>

<!-- se lo style è scoped rimane esclusivamente applicabile al template stesso -->
<style scoped> 

</style>
