<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <a
          href="#"
          target="_blank"
        >
          Menu1
        </a>
      </li>
      <li>
        <a
          href="#"
          target="_blank"
        >
          Menu2
        </a>
      </li>
      <li>
        <a
          href="#"
          target="_blank"
        >
          Menu3
        </a>
      </li>
      <li>
        <a
          href="#"
          target="_blank"
        >
          Menu4
        </a>
      </li>
      <br>
      <li>
        <a
          href="#"
          target="_blank"
        >
         
        </a>
      </li>
    </ul>
    
  </div>
</template>


<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: ''
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
  padding: 0;
  text-decoration: none;
}
li {
  display: inline-block;
  margin: 0 10px;

}
a {
  color: #000;
  text-decoration:none;
  
}
body, html {
  height: 100%;
  margin: 0;
  font-family: 'Noto Serif JP', sans-serif;
}


</style>
