<template>
  <div class="about-wrapper">
    <div class="w3-container w3-theme-d3 w3-mobile about-section">
      <div class="w3-container w3-mobile about-main">
        <h2>About me</h2>
      </div>
    </div>
    <VerticalLeftBar />
    <VerticalRightBar />
  </div>
</template>

<script>
import AboutMe from "../components/AboutMe";
import VerticalLeftBar from "../components/VerticalLeftBar";
import VerticalRightBar from "../components/VerticalRightBar";
export default {
  metaInfo: {
    title: "About Me",
  },
  components: {
    AboutMe,
    VerticalLeftBar,
    VerticalRightBar,
  },
};
</script>
