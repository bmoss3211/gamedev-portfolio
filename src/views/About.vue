<template>
  <main class="intro">
    <p class="role">Gameplay programmer &amp; technical designer</p>
    <h1>Brandon Moss</h1>
    <p class="lead">I build enemy encounters and gameplay systems. On <em>Call of Duty: Modern Warfare III — Zombies</em>, I designed enemy placement and encounter flow, scripted AI behaviors in GSC, and fixed gameplay bugs.</p>
    <router-link to="/game-projects">Explore my projects →</router-link>
    <figure>
      <img src="img/zombies.png" alt="Gameplay from Call of Duty: Modern Warfare III — Zombies" />
      <figcaption>Modern Warfare III — Zombies · Technical design</figcaption>
    </figure>
    <h2>Independent development</h2>
    <p><strong>Ghost Gaming · UEFN and Verse.</strong> As the sole developer, I designed original game modes, programmed their mechanics, and iterated on them in play.</p>
    <p><strong>Multiplayer VR shooter · Unity, C#, and Photon.</strong> I built this online first-person shooter solo for my Kennesaw State capstone, from VR interactions to multiplayer networking.</p>
    <router-link to="/resume">View my résumé →</router-link>
  </main>
</template>

<style scoped>
.intro { max-width: 52rem; text-align: left; }
.role, figcaption { font-size: .95rem; }
.intro h1 { margin: .2em 0 .45em; line-height: 1.1; font-weight: 700; }
.lead { max-width: 47rem; font-size: 1.2em; line-height: 1.55; }
.intro a { opacity: 1; text-decoration: underline; }
figure { margin: 1.5rem 0; }
figure img { width: 100%; height: auto; display: block; }
figcaption { margin-top: .35rem; }
</style>
