<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Drop files here to convert to or from .add
      <br />or other common Ambisonics deocoding matrix formats.
      <br />For exact specifications of .add,
      <br />check out the
      <a
        href="https://github.com/smp-3d/dotadd/blob/master/dotadd-spec/dotadd-spec.pdf"
        target="_blank"
        rel="noopener"
      >specifiction sheet</a>.
    </p>
    <h3>Essential Links</h3>
    <ul>
      <li>
        <a
          href="https://github.com/smp-3d/dotadd-converter"
          target="_blank"
          rel="noopener"
        >.add Converter</a>
      </li>
      <li>
        <a href="https://github.com/smp-3d/libdotadd" target="_blank" rel="C++ Library">C++ Library</a>
      </li>
      <li>
        <a href="https://github.com/smp-3d/dotadd.js" target="_blank" rel="noopener">JS Library</a>
      </li>
      <li>
        <a href="https://github.com/smp-3d/dotadd.py" target="_blank" rel="noopener">Python Library</a>
      </li>
      <li>
        <a href="https://github.com/smp-3d" target="_blank" rel="noopener">List of all .add Repos</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Info",
  props: {
    msg: String
  }
};
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
  color: #42b983;
}
</style>
