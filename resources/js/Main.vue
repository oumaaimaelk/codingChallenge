<template>
    <div >
  <navBar></navBar>
  
    <router-view></router-view>
    </div>
</template>

<script>
import navBar from './components/navBar' 
    export default {
        name: "Main",
        components: {
        navBar
        }
        }
   
</script>