<script>
export default {
  data: () => ({
    show: true
  })
}
</script>

<template>
  <div id="welcome">
    <img id="aiLogo" alt="Vue logo" src="../assets/img/aiLogo.png" />
    <h1 id="welcomeTitle">Welcome on board !</h1><br>
    <h2>What do you know about Artificial Intelligence ?</h2><br>
    <h2>Do we have to fear it or believe it ?</h2>
  </div>
</template>

<style scoped>
#welcome {
  color: white;
  text-align: center;
}
#aiLogo {
  margin-top: 100px;
  width: 35%;
}
#welcomeTitle {
  background: linear-gradient(to right, #ff59d4, #c603be);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
h2 {
  margin-top: 50px;
}
</style>
