<template>
  <div class="hello">
    {{value}}
  </div>
</template>

<script>
export default {
  name: 'test',
  data () {
    return {
      value: '这是ES6组件'
    }
  }
}
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
