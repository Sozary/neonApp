<template>
  <div id="app" class="lg:flex"><preview /><options /></div>
</template>

<script>
import Preview from "@/components/preview.vue";
import Options from "@/components/options.vue";

export default {
  components: { Preview, Options },
};
</script>

<style>
@font-face {
  font-family: "Neon-Script-Alexsandra Demo";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Alexsandra-Demo.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-alexandra {
  font-family: "Neon-Script-Alexsandra Demo";
}

@font-face {
  font-family: "Neon-Script-Amanda Signature";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Amanda-Signature.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-amanda {
  font-family: "Neon-Script-Amanda Signature";
}

@font-face {
  font-family: "Neon-Script-Barcelony";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Barcelony.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-barcelony {
  font-family: "Neon-Script-Barcelony";
}

@font-face {
  font-family: "Neon-Script-Assalwa";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Assalwa.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Neon-assalwa {
  font-family: "Neon-Script-Assalwa";
}

@font-face {
  font-family: "Neon-Script-Bayshore";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Bayshore.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Bayshore {
  font-family: "Neon-Script-Bayshore";
}

@font-face {
  font-family: "Neon-Script-Budhayanti Script";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Budhayanti-Script.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Budhayanti {
  font-family: "Neon-Script-Budhayanti Script";
}

@font-face {
  font-family: "Neon-Script-Gruenewald VA";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Gruenewald-VA.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Gruenewald {
  font-family: "Neon-Script-Gruenewald VA";
}

@font-face {
  font-family: "Neon-Script-Hamillton Demo";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Hamillton-Demo.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Hamillton {
  font-family: "Neon-Script-Hamillton Demo";
}

@font-face {
  font-family: "Neon-Script-Hesterica";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Hesterica.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Hesterica {
  font-family: "Neon-Script-Hesterica";
}

@font-face {
  font-family: "Neon-Script-La Patio";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/La-Patio-Script.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Patio {
  font-family: "Neon-Script-La Patio";
}

@font-face {
  font-family: "Neon-Script-Learning Curve";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Learning-Curve.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-learning {
  font-family: "Neon-Script-Learning Curve";
}

@font-face {
  font-family: "Neon-Script-Little Days";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Little-Days.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-littleDay {
  font-family: "Neon-Script-littleDay";
}

@font-face {
  font-family: "Neon-Script-Northwell Alt";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Northwell-Alt.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Northwell {
  font-family: "Neon-Script-Northwell Alt";
}

@font-face {
  font-family: "Neon-Script-Photograph Signature";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Photograph-Signature.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Photograph {
  font-family: "Neon-Script-Photograph Signature";
}

@font-face {
  font-family: "Neon-Script-Quinzey";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Quinzey.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Quinzey {
  font-family: "Neon-Script-Quinzey";
}

@font-face {
  font-family: "Neon-Script-Rocket Clouds DEMO";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Rocket-Clouds-DEMO.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Rocket {
  font-family: "Neon-Script-Rocket Clouds DEMO";
}

@font-face {
  font-family: "Neon-Normal-Bauhaus";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Bauhaus.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Bauhaus {
  font-family: "Neon-Normal-Bauhaus";
}

@font-face {
  font-family: "Neon-Normal-Circular Std Book";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Circular-Std-Book.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Circular {
  font-family: "Neon-Normal-Circular St Book";
}

@font-face {
  font-family: "Neon-Normal-Comfortaa";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Comfortaa.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Comfortaa {
  font-family: "Neon-Normal-Comfortaa";
}

@font-face {
  font-family: "Neon-Normal-Courier New";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Courier-New.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-courierNew {
  font-family: "Neon-Normal-Courier New";
}

@font-face {
  font-family: "Neon-Normal-Dolce Vita";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Dolce-Vita.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-DolceVita {
  font-family: "Neon-Normal-Dolce Vita";
}

@font-face {
  font-family: "Neon-Normal-Kiona";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Kiona.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Kiona {
  font-family: "Neon-Normal-Kiona";
}

@font-face {
  font-family: "Neon-Normal-Neon Club Music";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Neon-Club-Music.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-ClubMusic {
  font-family: "Neon-Normal-Neon Club Music";
}

@font-face {
  font-family: "Neon-Normal-Nixie One";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Nixie-One.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-nixieOne {
  font-family: "Neon-Normal-Nixie One";
}

@font-face {
  font-family: "Neon-Normal-Ostrich Sans Medium";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Ostrich-Sans-Medium.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-Ostrich {
  font-family: "Neon-Normal-Ostrich Sans Medium";
}

@font-face {
  font-family: "Neon-Normal-Paper Daisy DEMO";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Paper-Daisy-DEMO.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-PaperDaisy {
  font-family: "Neon-Normal-Paper DEMO";
}

@font-face {
  font-family: "Neon-Normal-Space Galaxy";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Space-Galaxy.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-SpaceGalaxy {
  font-family: "Neon-Normal-Space Galaxy";
}

@font-face {
  font-family: "Neon-Outline-Allstar";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Allstar.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-OutlineAllstar {
  font-family: "Neon-Outline-Allstar";
}

@font-face {
  font-family: "Neon-Outline-Double Cozy";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Double-Cozy.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-DoubleCozy {
  font-family: "Neon-Outline-Double Cozy";
}

@font-face {
  font-family: "Neon-Outline-Lovelo Line";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Lovelo-Line.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-OutlineLoveLoLine {
  font-family: "Neon-Outline-Lovelo Line";
}

@font-face {
  font-family: "Neon-Outline-Marquee Moon";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Marquee-Moon.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-OutlineMarqueeMoon {
  font-family: "Neon-Outline-Marquee Moon";
}

@font-face {
  font-family: "Neon-Outline-Metropolis 1920";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/Metropolis-1920.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-OutlineMetropolis1920 {
  font-family: "Neon-Outline-Metropolis 1920";
}

@font-face {
  font-family: "Neon-Outline-NEON GLOW";
  src: url("https://www.lcsign.com/wp-content/uploads/2021/01/NEON-GLOW.ttf")
    format("truetype");
  font-style: normal;
  font-weight: normal;
  font-display: auto;
}

.font-OutlineNEONGLOW {
  font-family: "Neon-Outline-NEONGLOW";
}
</style>
