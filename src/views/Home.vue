<template>
  <div>
    <h1>안녕하세요 helloworld</h1>
    <test1></test1>
    <form action="">
      <label for="">Name</label>
      <input type="text" v-model="name">
      <br><button>Submit</button>
    </form>

  </div>
</template>
<script>
import test1 from '@/components/test.vue';

export default {
  components: {
    test1
  },

  data() {
    return{
      name: '작성자 : 한재철'
    }
  }
}
</script>
<style scoped>
 h1 {
   color:red;
 }
</style>