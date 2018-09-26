<template>
    <div class="hello2">
        <h1>{{ msg }}</h1>
        <h2>我是测试页面</h2>
    </div>  
</template>
<script>
export default {
  name: 'Test',
  data () {
    return {
      msg: '123456'
    }
  }
}
</script>

<style scoped>
h1,h2{
    font-weight: normal;
    color: brown;
}
</style>



