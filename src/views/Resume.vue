<template>
  <div>
    <h1>Resume</h1>

    <div class="paragraph">
      Former Call of Duty developer with experience, drive, and an unyielding passion for technology. From the AAA video game Call of Duty
      Modern Warfare III to apps to control your car, I love working on projects that impact people. I strive in a team while working well
      independently to get tasks done under strict time constraints.
      <br />
      <br />Right now I'm trying to find a new role so if you have any opportunities feel free to
      <router-link to="/contact">contact me</router-link>.
      <br />
      <br />Besides development, I'm passionate about songwriting and music.

      <div style="margin-top:20px; margin-bottom:20px;">
        <a class="download-link" href="d/resume.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF</a>
        <div style="clear:both"></div>
      </div>
    </div>
    <div class="photo">
      <img src="img/resume-photo.png" alt="Photo of Brandon" />
    </div>

    <div style="clear:both"></div>

    <div class="full-content">
      <h2>Work experience</h2>

      <h3>Associate Technical Designer - Microsoft/Activision-Blizzard (Sledgehammer Games)</h3>
      <h4>July 2022 - January 2024</h4>

      <div>• Programmed in a proprietary game language "Game Script Code" (Call of Duty's version of C#) in a proprietary game engine,
        simultaneously learning new systems and implementing game mechanics for the latest blockbuster Call of Duty title.<br />
        • Designed, prototyped, integrated, and refined game features experienced by millions of players around the globe.<br />
        • Came up with new ideas that fit the vision of the game and interfaced with other designers to improve upon said ideas.<br />
        • Collaborated with a versatile team of designers, engineers, and artists.<br />
        • Debugged and parsed logs to fix issues that arose.<br /></div>

      <div class="tech-stack">CODEngine, GSC, LUA, Agile, Jira, Confluence, Design, Source Control</div>

      <h3>Application Developer - Comcast</h3>
      <h4>April 2022 - July 2022</h4>

      <div>• Designed, implemented, and maintained new features and experiences in the Comcast Android app using a combination of C# and .NET and
        native Java and Kotlin.<br />
        • Collaborated closely with iOS and Backend engineers, Product Owners, Designers, and Business Stakeholders on projects.<br />
        • Participated in and supported bi-weekly Play Store releases to millions of users, closely monitoring product stability, feature releases,
        analytics, and experiments.<br />
        • Built durable, well-tested code with a strong commitment to quality and testability.<br />
        • Worked with the latest Jetpack & Kotlin tools and frameworks.<br /></div>

      <div class="tech-stack">Kotlin, Java, Jira, Confluence, Agile, Source Control</div>

      <h3>Application Developer - Ford Motor Company</h3>
      <h4>September 2021 - April 2022</h4>

      <div>• Developed Android applications from conception to production for drivers and vehicles around the world using native Java.<br />
        • Actively participated in reviewing, evaluating, and providing feedback on product designs and architectures with a software engineering
        focus.<br />
        • Wrote and contributed to high-quality documentation for software engineers.<br />
        • Worked effectively with product managers, product designers and other technical experts.<br /></div>

      <div class="tech-stack">Kotlin, Java, Confluence, Agile, Source Control</div>

      <h3>Software Engineer - Makro Gaming Studios</h3>
      <h4>November 2020 - September 2021</h4>

      <div>• Ported existing casino titles to Android and iOS respecting mobile device limitations using C#, .NET, and Unity.<br />
        • Collaborated with artists to ensure uniformity across mobile and machine games.<br /></div>

      <div class="tech-stack">Unity, C#, Jira, Confluence, Agile, Source Control</div>

      <h3>Application Developer - Materialize, Inc</h3>
      <h4>November 2020 - September 2021</h4>

      <div>• Designed and implemented features for an eSports management Android application.<br />
        • Collaborated with product and design teams to optimize the mobile user experience.<br />
        • Resolved design and development issues as they arose, ensuring the inclusion of a business vision and adjusting to new industry trends<br /></div>

      <div class="tech-stack">Kotlin, Java, Jira, Confluence, Agile, Source Control</div>

      <h2>Skills</h2>

      <div class="skill-set">
        <SkillRate name="C#, C++, .NET, GSC, Unreal Engine 4+, Unity 5+, Java, Kotlin, Lua, AGILE, Scrum, Proprietary Engines" />
      </div>
      <div style="clear:both" />

      <h2>Education</h2>

      <h3>Kennesaw State University 2015 - 2019</h3>
      <h4>Bachelor of Science in Computer Game Design and Development</h4>
      <div>• Researched AR, VR, and motion capture to explore contemporary systems, resulting in a fully functional online VR first-person shooter as
        my Capstone project.<br />
        • Game Design and Development Club (GDDC) President/Event Coordinator - planned large-scale events, led meetings, and taught game
        design fundamentals to new students.<br />
        • Residence Hall Association (RHA) President - created a sense of community through planning multi-campus events, leading town hall
        meetings, and acting as liaison between the student body and school faculty.<br /></div>

      <h2>Certifications</h2>
      <div>
        <h3>Unity Official Ceritification 2017 - 2019</h3>
        <div>
          <a href="https://www.credly.com/badges/6ff40796-15f3-45f3-9829-f8e8c7537785/linked_in" target="">Link</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    SkillRate,
  },
});
</script>

<style scoped>
h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}
h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float:left;
  margin-right: 50px;
}

.full-content div {
  max-width: 800px;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.photo img {
  height: 300px;
  width: 300px;
}

.tech-stack {
  font-style: italic;
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
    padding: 30px;
    padding-left: 80px;
  }

  .skill-set {
    float: left;
    padding-right: 60px; 
  }
}
</style>