<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Para más información visita la página oficial de
      <a href="https://bluelock-pr.com/news/1820/" target="_blank" rel="noopener">BLUELOCK</a>.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: magenta;
}
</style>
