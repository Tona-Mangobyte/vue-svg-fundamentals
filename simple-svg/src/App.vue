<template>
  <img
      width="1024"
      height="768"
      alt="Vue logo"
      src="./assets/IP-914-2.png"
      class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2"
  >
  <svg
      id="svg"
      width="1024"
      height="768"
      class="absolute left-1/2 top-1/2 -translate-x-1/2 -translate-y-1/2"
  >
    <g
        :transform="`translate(310, 379)`"
    >
      <circle
          class="cursor-pointer fill-current text-transparent"
          cx="1" cy="0" r="15"
          fill="#008CD6"
          @click="() => clickMe()"
          stroke="red"
          />
    </g>
  </svg>

  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  methods: {
    clickMe() {
      console.log('clicked')
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
