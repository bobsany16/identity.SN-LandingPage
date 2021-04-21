<template>
  <div id="About" class="about-wrapper">
    <!--<VerticalHomeBar />-->
    <div class="w3-container w3-mobile about-section">
      <div class="w3-container w3-half w3-mobile about-main">
        <h2><em>ABOUT ME</em></h2>
        <p>
          I am a software developer with experience in mobile & web
          applications. I build cool, reusable components, and features for
           <g-link
            class="w3-hover-text-theme3"
            to="https://meanguppy.com"
          >Mean Guppy</g-link>, a design-technology firm in Buffalo, NY.
          I enjoy my work as I get to learn so many new things each day.
          <br />
          <br />
          A fun fact about me: I take roughly 8 - 10 small breaks per work day. I find it extremely
          important and beneficial for my work flow.
          <br /><br />My Skills:
          
        </p>
        <div class="skills_icon">
          <font-awesome :icon="['fab', 'js-square']" size="3x" class="skills"/>
          <font-awesome :icon="['fab', 'react']" size="3x" class="skills" />
          <font-awesome :icon="['fab', 'html5']" size="3x" class="skills" />
          <font-awesome :icon="['fab', 'css3']" size="3x" class="skills" />
          <font-awesome :icon="['fab', 'python']" size="3x" class="skills" />
          <font-awesome :icon="['fab', 'java']" size="3x" class="skills" />
          <font-awesome :icon="['fab', 'vuejs']" size="3x" class="skills" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AboutMe",
};
</script>
