<template lang="pug">
div(style=`width: 100%; display: flex;
           flex-direction: column;`)
  #hdr(style=`border: 2px solid black; width: 100%;
              position: fixed; left: 0; top: 0;
              background-color: yellow;
              flex-basis: 2.5em;`)
    div(style=`padding: 0 1em; display: flex;`)
      div(style=`font-weight: bold; font-size: 1.5em;
                  flex-basis: 2.5em; margin-top: .25em;`) SSJ
      input(v-model="topExpr" @input="topExprInput"
            style=`border: 2px solid black; height: 1.5em;
                   font-size: 1.2em; flex-grow: 2; margin: .25em 0;`)
  #desk(style=`flex-grow: 2;
               position: fixed; left: 0; top: 2.8em;
               border: 2px solid black; width: 100%;`)
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
