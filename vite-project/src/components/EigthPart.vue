<script>
export default {
  data: () => ({
    show: true
  })
}
</script>

<template>
  <div id="eigthPart" class="sectionMargin">
    <h2 class="sectionTitle">Robotics of everyday life</h2>
    <div class="divided">
      <div class="midWidth">
        <h3>It is increasingly found in the field of agriculture with new, ingenious and increasingly complex machines that make it easier for farmers to do their jobs. Beyond the already (almost) democratized drones, many new robotic tools are emerging, allowing better crop control and work done more quickly and efficiently. For example, MIT students have developed an automatic fruit harvesting system. The system is based on a network of sensors measuring plant moisture. She then communicates directly with the robot for watering or harvesting if necessary. Rowbot, supported by former Carnegie Mellon researchers, allows him to collect data on wheat ears and feed them with fertiliser if necessary, all in a 100% autonomous way. A unique asset for farmers who can let this robot perform its tasks without much help from humans and provide a better harvest while optimizing time management.</h3>
        <img src="../assets/img/rowbot.jpg" alt="">
      </div>
      <div class="midWidth">
        <h3>Another example within the field of agriculture and a significant technological contribution, the RoboBee. RoboBee is inspired by the biology of a bee, researchers are developing RoboBees, artificial systems that could reproduce the pollination process of bees with robots-A RoboBee is about half the size of a paper clip, weighs less than a tenth of a gram and flies using «artificial muscles» composed of materials that contract when a voltage is applied. These robots are also being further developed to enable some RoboBee models to move from underwater swimming to flying, as well as to 'perch' on surfaces using static electricity. It is thanks to the laboratories' recent breakthroughs in manufacturing, materials and design that these robots have been created. These small machines could revolutionize the world of agriculture and perhaps much more.</h3>
        <img src="../assets/img/robobee.jpeg" alt="">
      </div>
    </div>
  </div>
</template>

<style scoped>
.midWidth h3 {
  padding-right: 50px;
}
.midWidth img {
  display: flex;
  margin: 20px auto 0;
  width: 65%;
}
.midWidth:last-child img {
  width: 55%;
}
</style>
