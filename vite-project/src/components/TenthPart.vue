<script>
export default {
  data: () => ({
    show: true
  })
}
</script>

<template>
  <div id="tenthPart" class="sectionMargin">
    <h2 class="sectionTitle">Deepfakes</h2>
    <h3>We can see it with this video that shows several videos that appear real and without fakes, where we recognize Mark zuckerberg or President Obama or Trump but only they are not the ones who speak and move, it is other people who make this speech and with the technologies we have just seen, they can change the person’s voice and face to make it seem like this or that person. The problem with these videos is that at first sight one can only believe that they are really Obama or Trump and this can lead to mass misinformation and rumours about words that this “personality” would have said and thus harm the latter. It is rather difficult even for experts to analyze a video and deduce its veracity or not. As deepfake technologies evolve quite quickly it is therefore also increasingly difficult to determine whether or not a video is a deepfake. The videos we saw were created by Bill Posters who co-created Spectre, an art project. Mark Zuckerberg talks convincingly about how he controls millions of personal data. The video went viral. Then, Posters created fake videos of Donald Trump, Kim Kardashian and Freddie Mercury to show the possibilities.</h3>
    <iframe width="760" height="515" src="https://www.youtube.com/embed/NbedWhzx1rs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</template>

<style scoped>
#tenthPart h3 {
  margin-top: 50px;
  padding-right: 50px;
}
#tenthPart iframe {
  display: flex;
  margin: 50px auto 0;
}
.quartWidth {
  width: 25%;
}
.thirdWidth {
  width: 75%;
}
</style>
