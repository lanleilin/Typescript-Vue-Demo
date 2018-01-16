<template>
  <div class="hello">
    {{welcomeMsg}}
    <Test></Test>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Test from './Test.vue'
export interface Data {
  welcomeMsg: string,
  appName: string
}

export default Vue.extend({
  data (): Data {
    return {
      welcomeMsg: '这是TS组件',
      appName: 'ts+vue'
    }
  },

  components: {
    Test
  }
})
</script>

<style>
  h1, h2 {
    font-weight: normal;
  }

  ul {
    list-style-type: none;
    padding: 0;
  }

  li {
    display: inline-block;
    margin: 0 10px;
  }

  a {
    color: #42b983;
  }
</style>
