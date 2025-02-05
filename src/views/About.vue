<template>
  <div style="margin-bottom: 80px;">
    <h1>Hello!</h1>

    <div class="paragraph">
      <div>
        I am <strong>Brandon Moss</strong>, a versatile software developer and game designer with 5 years of experience across game development, mobile apps, and interactive simulations.
      </div>
      <div style="margin-top: 20px;">
        My background spans AAA game design, mobile app development, and Unity programming, allowing me to bridge the gap between design and engineering to create engaging, high-quality experiences.
      </div>
      <div style="margin-top: 20px;">Previously, I worked as a <strong>Technical Game Designer</strong> at <strong>Microsoft/Activision-Blizzard's Sledgehammer Games</strong>,
        where I contributed to the development of <router-link to="/game-projects">Call of Duty: Modern Warfare III's</router-link> gameplay systems, design, and stability. Before that, I developed <router-link to="/resume">Android/iOS applications, casino games, and VR training simulations</router-link> primarily using Unity.
      </div>
      <div style="margin-top: 20px;">
        I'm passionate about crafting immersive experiences and currently looking for a new role. You can reach me at <a href="mailto:brandonallen.moss@gmail.com">brandonallen.moss@gmail.com</a> or <router-link to="/contact">through this page</router-link>.
      </div>
      <div style="margin-top: 20px;">
      Let's connect and create something amazing!
      </div>
    </div>

    <div class="photo">
      <img src="img/avatar.png" alt="Avatar of Brandon" />
    </div>

    <div style="clear:both"></div>

  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}

</style>
<script lang="ts">
</script>