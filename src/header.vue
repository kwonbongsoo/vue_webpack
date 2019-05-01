<template>
  <div class="m_header">
    <div @click="clickAlert">메뉴3</div>
    <div>메뉴2</div>
    <div>메뉴1</div>
  </div>
</template>

<script>
import HelloWorld from './HelloWorld.vue'
export default {
  name: 'app',
  data: () => {
    return {
     a: 1, 
    }
  },
  mounted() {
    console.log(this.arr);
    console.log(this);
  },
  extends: HelloWorld 
}
</script>
<style scoped>
.m_header {
  display: flex;
  flex: 0 1 auto;
  justify-content: center;
  align-items: center;
  background-color: navy;
  height: 60px;
}
.m_header > div {
  color: white;
  font-weight: white;
  font-size: 5vw;
}
</style>



