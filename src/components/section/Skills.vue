<template>
  <v-container>
    <v-card>
      <v-col cols="12">
        <v-row>
          <v-card-title style="text-decoration: underline; font-size: 22px;">
            <b>Skills and spoken languages</b>
          </v-card-title>
        </v-row>

        <v-row>
          <v-col cols="2">
            <v-card height="100%" variant="flat">
              <v-card-title>
                Soft skills
              </v-card-title>

              <v-card-item>
                <li>Adaptability</li>
                <li>Teamworking</li>
                <li>Creativity</li>
                <li>Empathy</li>
              </v-card-item>
            </v-card>
          </v-col>

          <v-col cols="3">
            <v-card height="100%" variant="flat">
              <v-card-title>
                Programming skills
              </v-card-title>

              <v-card-item>
                <li>C / C++ / C#</li>
                <li>Web (PHP, JS, HTML, CSS)</li>
                <li>SQL</li>
                <li>Python</li>
              </v-card-item>
            </v-card>
          </v-col>

          <v-col cols="3">
            <v-card height="100%" variant="flat">
              <v-card-title>
                Software
              </v-card-title>

              <v-card-item>
                <li>Office</li>
                <li>Talend</li>
                <li>Postman</li>
                <li>Git</li>
              </v-card-item>
            </v-card>
          </v-col>

          <v-col cols="4">
            <v-card height="100%" variant="flat">
              <v-card-title>
                Languages
              </v-card-title>

              <v-card-item>
                <v-row>
                  <v-col cols="4">English (850 TOEIC)</v-col>
                  <v-col cols="8">
                      <v-progress-linear height="10" striped style="position: relative; top: 10px" model-value="80" color="green"></v-progress-linear>
                  </v-col>
                </v-row>
              </v-card-item>

              <v-card-item>
                <v-row>
                  <v-col cols="4">Spanish</v-col>
                  <v-col cols="8">
                    <v-progress-linear height="10" striped style="position: relative; top: 10px" model-value="10" color="green"></v-progress-linear>
                  </v-col>
                </v-row>
              </v-card-item>
            </v-card>
          </v-col>
        </v-row>
      </v-col>
    </v-card>
  </v-container>
</template>

<script>

export default {
  name: 'HelloWorld'
}
</script>
