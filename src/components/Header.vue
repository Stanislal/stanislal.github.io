<template>
  <div id="Header">
    <header>
      <h1>Header Content</h1>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100" preserveAspectRatio="none">
        <polygon fill="white" points="0,100 00,0 100,100" />
      </svg>
    </header>
  </div>
</template>

<script>

export default {
  name: 'Header',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="less" scoped>
h1 {
  padding: 100px 0;
      margin-top: 0;
  font: 44px "Arial";
  text-align: center;
}

header h1 {
  color: white;
}
header {
  position: relative;
  height: 300px;
  background-image: linear-gradient(#ff9d2f, #ff6126);

  svg {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 10vw;
    /* set height to pixels if you want angle to change with screen width */
  }
}
</style>
