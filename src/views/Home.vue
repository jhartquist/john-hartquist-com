<template>
  <v-container>
    <v-row>
      <v-col>
        <v-card flat max-width="620">
          <v-card-title class="text-h4 font-weight-bold">
            John Hartquist
          </v-card-title>

          <v-card-subtitle class="text-h6 mb-2">
            <p>Software Engineer - ML</p>
            <p>Seattle, WA</p>
          </v-card-subtitle>
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title>Interests</v-list-item-title>
              <v-list-item-subtitle
                >Real-time Audio Analysis, DSP, VR/AR, Deep Learning, Functional
                Programming, Reinforcement Learning, Prototyping
              </v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>

          <v-list-item>
            <v-list-item-content>
              <v-list-item-title>Preferred Languages</v-list-item-title>
              <v-list-item-subtitle
                >Python, TypeScript, Scala</v-list-item-subtitle
              >
            </v-list-item-content>
          </v-list-item>

          <v-list-item>
            <v-list-item-content>
              <v-list-item-title>Expertise</v-list-item-title>
              <v-list-item-subtitle
                >Deep Learning, Audio Programming, Full-Stack Web Development,
                Test-Driven Development, Data Engineering, SQL, Data
                Visualization, Distributed Systems, Serverless Computing,
                Optimization, Parallel Programming</v-list-item-subtitle
              >
            </v-list-item-content>
          </v-list-item>

          <v-list-item>
            <v-list-item-content>
              <v-list-item-title>Education</v-list-item-title>
              <v-list-item-subtitle
                >MS Computer Science '12<br />
                California Polytechnic State University</v-list-item-subtitle
              >
            </v-list-item-content>
          </v-list-item>

          <v-list-item>
            <v-list-item-content>
              <v-list-item-title>Experience</v-list-item-title>
              <v-list-item-subtitle
                ><a
                  href="https://www.linkedin.com/in/john-hartquist/"
                  target="_blank"
                  >LinkedIn Profile</a
                ><br />
                <a href="/John_Hartquist_Resume.pdf" target="_blank"
                  >Resume (PDF)</a
                ></v-list-item-subtitle
              >
            </v-list-item-content>
          </v-list-item>

          <v-list-item>
            <v-list-item-content>
              <v-list-item-title>Blog Posts</v-list-item-title>
               <v-list-item-subtitle>
                <a
                  href="https://wandb.ai/jhartquist/fastaudio-esc-50/reports/Fine-tuning-ResNet-18-for-Audio-Classification--VmlldzoyNjU3OTQ"
                  target="_blank"
                  >Fine-tuning ResNet-18 for Audio Classification</a
                ></v-list-item-subtitle
              >
              <v-list-item-subtitle>
                <a
                  href="https://towardsdatascience.com/audio-classification-using-fastai-and-on-the-fly-frequency-transforms-4dbe1b540f89"
                  target="_blank"
                  >Audio Classification using FastAI and On-the-Fly Frequency
                  Transforms</a
                ></v-list-item-subtitle
              >
            </v-list-item-content>
          </v-list-item>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<style lang="scss">
.v-application {
  .v-card__subtitle p {
    margin-bottom: 0;
  }
  .v-list-item__subtitle {
    margin-top: 4px;
    white-space: normal;
    a {
      color: #999;
      text-decoration: underline;
      &:hover {
        text-decoration: none;
        color: #666;
      }
    }
  }
}
</style>
