<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  data:{
    cards: [
      {name: 'Apple', img: 'apple.gif', },
      {name: 'Banana', img: 'banana.gif',},
      {name: 'Orange', img: 'orange.jpg',},
      {name: 'Pineapple', img: 'pineapple.png',},
      {name: 'Strawberry', img: 'strawberry.png',},
      {name: 'watermelon', img: 'watermelon.jpg',}
            
    ],
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
