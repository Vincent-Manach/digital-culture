<script>
export default {
  data: () => ({
    show: true
  })
}
</script>

<template>
  <div id="sixthPart" class="sectionMargin">
    <h2 class="sectionTitle">Robotics of everyday life</h2>
    <div class="divided">
      <div class="midWidth">
        <h3>So let’s take the example of robots that are counted in medicine today and that bring a real added value. In the related field of well-being, robotics is making a remarkable entrance via the Social Robots. A social robot is an autonomous robot that interacts and communicates with humans or other autonomous physical agents by following social behaviors and rules attached to its role. Like other robots, a social robot is physically embodied (avatars or synthetic social characters on the screen are not embodied and therefore distinct). Some synthetic social workers are designed with a screen to represent the head or the «face» to communicate dynamically with users. In these cases, the social robot status depends on the shape of the social agent’s «body»; if the body possesses and uses physical motors and sensor capabilities, then the system could be considered a robot. And here is a very good example of a social robot with Milo.</h3>
        <br>
        <h3>Milo is a robot companion for children with autism who aims to accompany the child in his capacity of adaptation in society and at school from an early age. He can walk, talk and even model human facial expressions. Milo is never frustrated or tired. Milo gives verbal lessons. As he speaks, symbols are displayed on his chest screen that will help the child better understand what he is saying. Throughout the lessons, Milo will ask the child to watch four to five second video clips on the student’s tablet. The videos show children displaying skills or behaviors both correctly and incorrectly taught by Milo. The child will be asked “yes” or “no” questions to determine whether the children in the video are behaving well or poorly.</h3>
      </div>
      <div class="midWidth">
        <img src="../assets/img/milo.jpg" alt="">
      </div>
    </div>
  </div>
</template>

<style scoped>
.midWidth img {
  width: 80%;
  margin: 0 0 0 75px;
}
.sectionTitle {
  margin-bottom: 130px;
}
@media screen and (min-width: 1500px) and (max-width: 1700px) {
  .midWidth img {
    margin: 25px 0 0 75px;
  }
}
</style>
