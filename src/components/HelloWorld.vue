<template>
  <div class="hello">
    <h1>IDEA在线调试VUE脚本,不用F5或者Vue插件了!</h1>
    <button @click="helloPop">开始调试Vue Script</button>
  </div>
</template>

<script>

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
    return{
      localMsg:"调试信息"
    }
  },
  methods: {
    helloPop(){
      console.log(this.msg)
      console.log("Idea 可以在线调试Vue Script!!!!")
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
</style>
