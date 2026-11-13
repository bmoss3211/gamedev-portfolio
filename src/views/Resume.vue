<template>
  <main class="resume">
    <h1>Brandon Moss</h1>
    <p>Gameplay programmer &amp; technical designer</p>
    <p><button type="button" @click="printResume">Print or save résumé as PDF</button></p>
    <h2>Game development experience</h2>
    <h3>Ghost Gaming · Resident Developer</h3>
    <p>Designed original game modes in UEFN as the sole developer. Programmed mechanics and interactive systems in Verse and debugged them through iteration.</p>
    <h3>Activision Blizzard · Technical Designer</h3>
    <p>2022–2024 · Call of Duty: Modern Warfare III — Zombies</p>
    <p>Designed enemy placement and encounter flow. Scripted AI behaviors and decision logic in GSC, implemented gameplay systems, and investigated AI and gameplay defects.</p>
    <h3>Makrö Gaming Studios · Unity C# Mobile Developer</h3>
    <p>2020–2021 · Adapted cabinet slot games for Android and iOS, translating gameplay and interfaces to touchscreen devices in Unity and C#.</p>
    <h2>Education and solo project</h2>
    <p>Kennesaw State University · B.S. in Computer Game Design and Development, 2019</p>
    <p>Designed and built an online multiplayer VR first-person shooter in Unity and C#. Implemented VR interactions, first-person gameplay, and multiplayer networking with Photon.</p>
    <h2>Tools and languages</h2>
    <p>UEFN, Unreal Engine, Blueprints, Unity, Call of Duty Engine, Photon · Verse, GSC, C#, C++, Python, Java, Kotlin</p>
  </main>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  methods: {
    printResume() {
      window.print();
    }
  }
});
</script>

<style scoped>
.resume { max-width: 48rem; text-align: left; }
.resume h1 { margin-bottom: .4em; line-height: 1.1; }
.resume h2 { margin: 1.6em 0 .6em; }
.resume h3 { margin: 1em 0 .2em; }
.resume p { margin: .35em 0 .8em; }
.resume button { font: inherit; color: inherit; background: transparent; border: 1px solid currentColor; border-radius: .25rem; padding: .25rem .8rem; cursor: pointer; }
@media print { .resume button { display: none; } }
</style>
