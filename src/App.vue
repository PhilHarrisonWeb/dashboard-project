
<template> 
<AppContainer> 
  <AppHeader /> 
  <AppSideBar />
</AppContainer>

</template>

<script >

import AppContainer from './components/layout/AppContainer.vue'
import AppHeader from './components/layout/AppHeader.vue'
import AppSideBar from './components/layout/AppSideBar.vue'
export default {
  name: 'App',
  components: {
    AppContainer,
    AppHeader,
    AppSideBar,
},
}

</script>

<style> </style>
