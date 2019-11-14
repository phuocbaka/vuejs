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
ul{
	display: flex;
	width: 100%;
	margin: auto;
	max-width: 1000px;
	justify-content: space-between;
	text-align: center;
  padding: 0;
  list-style: none;
}
li {
	padding: 1rem 2rem 1.15rem;
  text-transform: uppercase;
  cursor: pointer;
  color: #ebebeb;
	min-width: 80px;
	margin: auto;
}

li:hover {
  background-image: url('http://scottyzen.com/cp/button.png');
  background-size: 100% 100%;
  color: #000;
  animation: spring 300ms ease-out;
  text-shadow: 0 -1px 0 #ef816c;
	font-weight: bold;
}
li:active {
  transform: translateY(4px);
}

@keyframes spring {
  15% {
    -webkit-transform-origin: center center;
    -webkit-transform: scale(1.2, 1.1);
  }
  40% {
    -webkit-transform-origin: center center;
    -webkit-transform: scale(0.95, 0.95);
  }
  75% {
    -webkit-transform-origin: center center;
    -webkit-transform: scale(1.05, 1);
  }
  100% {
    -webkit-transform-origin: center center;
    -webkit-transform: scale(1, 1);
  }
}

.shameless-plug{
  position: absolute;
  bottom: 10px;
  right: 0;
  padding: 8px 20px;
  color: #ccc;
  text-decoration: none;
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
