<template>
  <div class="m_header">
    <div>메뉴1</div>
    <div>메뉴2</div>
    <div>메뉴3</div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data: () => {
    return {
      arr: [1,2,3]
    }
  },
  mounted () {
    console.log(3);
  },
  methods: {
    clickAlert() {
      alert(1);
    }
  }
}
</script>
<style scoped>
.m_header {
  display: flex;
  flex: 0 1 auto;
  justify-content: center;
  align-items: center;
  background-color: black;
  height: 60px;
}
.m_header > div {
  color: white;
  font-weight: white;
  font-size: 5vw;
}
</style>



