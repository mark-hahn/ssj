<template lang="pug">
#vport(style=`width: 100vw; height: 100vh; display: flex;
              flex-direction: column;`)
  #hdr(style=`width: 100vw; border-radius: .5em;
              background-color: yellow;
              flex-basis: 2em; display: flex;`)
    span(style=`font-weight: bold; font-size: 1.5em;
                flex-basis: 2em; margin: .25em 0 0 .5em;`) SSJ
    input(v-model="topExpr" @input="topExprInput"
          style=`border: 2px solid black; 
                 height: 1.5em; margin: .25em 0;
                 font-size: 1em; flex-grow: 1;`)
  #desk(style=`width: 100vw; flex-grow: 1;
               position: relative;`)
    div(style=`position: absolute; 
               border: 2px solid black; 
               top: 1em; left: 1em; `) test 
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: "App",
  
  components: { },

  data() {
  },

  methods: {
  }
}

</script>
