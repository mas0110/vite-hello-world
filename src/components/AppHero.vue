<script>
export default{
    name: "AppTitle"
}

</script>

<template>
  <div>
    <h2>questa è la hero</h2>
  </div>
</template>

<style scoped>
  div{
    background-image: url(/src/assets/img/Hero.jpg);
    background-size:cover ;
    height: 500px;
    position: relative;
  }
  h2{
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translateX(-50%) translateY(-50%);
    background-color: cyan;
    padding: 10px;
    border-radius: 10px 20px;


  }
</style>
