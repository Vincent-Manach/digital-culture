<script>
export default {
  data: () => ({
    show: true
  })
}
</script>

<template>
  <div id="firstPart" class="sectionMargin">
    <h2 class="sectionTitle">First, what is the artificial intelligence?</h2>
    <div id="definition">
      <div id="definitionDesc">
        <p>Artificial intelligence (AI) is the ability of a digital computer or computer-controlled robot to perform tasks commonly associated with intelligent beings. Moreover, the artificial intelligence is also about the fact that those computers, robots or machines can learn by themselves by repeating a processus of learning over and over.</p><br>
        <p>The very beginning of the reflection about the AI came first with Alan Turing and his question "Can machines think ?". Thanks to Alan and his relfection we have today lot of machines that can do several tasks</p>
      </div>
      <div id="definitionImg">
        <img src="../assets/img/ai.jpg" alt="AI image">
      </div>
    </div>
  </div>
</template>

<style scoped>
#definition {
  display: flex;
  margin: 100px auto 0;
  width: 80%;
}
#definitionDesc {
  display: flex;
  flex-direction: column;
  width: 50%;
  padding: 50px;
  border: 1px solid white;
  border-radius: 6px;
}
#definition p {
  font-size: 1.6em;
}
#definitionImg {
  width: 50%;
  text-align: center;
}
#definitionImg img {
  width: 80%;
  margin: 50px auto 0;
}
@media screen and (min-width: 1500px) and (max-width: 1700px) {
  #definitionImg img {
    margin: 125px auto 0;
  }
}
</style>
