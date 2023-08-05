<template>
  <div id="main-banner">
    <h1>Make Your Precious</h1>
  </div>
</template>

<script>
export default {
  name: 'Banner'
};
</script>

<style lang="scss" scoped>
#main-banner {
  background: url('../../public/img/burger.jpg') no-repeat;
  background-position: 0px -275px;
  background-size: cover;
  height: 80vh;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  h1 {
    background-color: #222;
    color: #fff;
    text-align: center;
    font-size: 3.75rem;
    padding: 20px 40px;
    border-radius: 0 20px 20px 0;
  }
}
</style>
