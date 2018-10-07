<template>
  <div class="search">
    <form v-on:submit.prevent="getResult(query)">
      <input type="text" v-model="query" />
    </form>
  </div>
</template>

<script>
export default {
  name: 'Search',
  data () {
    return {
      msg: 'Search App',
      query: 'Eric'
    }
  },
  methods: {
    getResult(query) {
      alert(query);
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
