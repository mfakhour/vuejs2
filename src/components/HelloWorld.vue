<template>
  <div>
    <h1>ITSP Parameters Management Rest APIs</h1>
    <a href="https://s2mworldwide.com/" class="link-success">click here</a>
  </div>

  <div id="app" v-for="item in data.tags" :key="item">
        
         <h1>{{item.name}}</h1>
         <a href="#" class="link-success">{{item.description}}</a>
        
    
  </div>
  
</template>

<script>
import apiData from "./api.json";

export default {
  data() {
    return {
      data: apiData,
    };

  },
};
</script>
<style>

</style>
