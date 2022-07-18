<template>
  <div>
    {{ msg }}
    <br>
    {{ test }}
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data(){
    return{
      test:"hello",
    }
  },
  props: {
    //prop   ------>  可以通过外界的标签栏函数进行调用实现外部函数式赋值
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
