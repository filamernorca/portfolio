<template>
  <div class="container-fluidp-0">
  <Nav />
  <Intro/>
  <Academics/>
  <Hobbies/>
  <Sports/>
  <Photography & Editing/>
  </div>
  </template>

  <script> 
  import Nav from './components/Nav.vue' 
  import Intro from './components/Intro.vue' 
  import Academics from './components/Academics.vue' 
  import Hobbies from './components/Hobbies.vue' 
  import Sports from './components/Sports.vue' 
  import Photography from './components/Photography.vue' 
  
  export default { 
    name: 'App', 
    components: 
    { Nav, 
    Intro, 
    Academics, 
    Hobbies, 
    Sports, 
    Photography
    } } </script>