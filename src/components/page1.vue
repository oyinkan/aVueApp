<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <router-link to="/page2">Go to questions' page</router-link>

  </div>
</template>

<script>
export default {
  name: 'Page1',
  data () {
    return {
      msg: 'Test your fit to work'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
