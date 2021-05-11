<template>
  <div>
    <div class="hello">
      <h1>{{ msg }}</h1>
    </div>
    <p>
      Input: Array of Number. ( Number >=0 &amp;&amp; Number &lt; 1000). Array's length &lt; 100,000
    </p>
    <p>
      output: biggist number of combined Input.
    </p>
    <blockquote>
      i.g ) input is [6,1,40], combined Input can be '6140', '6401', '1640', '4061', '4016'm so the biggist number is '6401'. output must be '6401'
    </blockquote>
    <p>1. Please write a function for generating input arrays when you click 'run' button. 
    </p>
    <p>2. Please write a <a href="https://vuejs.org/v2/guide/computed.html">computed Property</a> for getting output number.</p>
    <button @click="run">Run</button>
    <p>inupt: {{input}}</p>
    <p>result: {{result}}</p>
  </div>
</template>


<script>

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      input: [],
      result: ''
    }
  },
   methods: {
    run () {
    }

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
  color: #42b983;
}
.hello {
  text-align: center;
}
</style>
