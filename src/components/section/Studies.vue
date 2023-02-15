<template>
  <v-container>
    <v-card>
      <v-col cols="12">
        <v-row>
          <v-card-title style="text-decoration: underline; font-size: 22px">
            <b>Studies</b>
          </v-card-title>
        </v-row>

        <v-col>
          <v-timeline density="compact">
            <v-timeline-item size="x-small" dot-color="rgb(9, 99, 114)">
              <div>
                CESI Engineering School (<b>2021 - 2024</b>)
              </div>
              <div>
                <b>Engineering cycle in IT speciality</b>
                <ul style="margin-left: 20px">
                  <li>Network (routing, lan, firewall, DMZ)</li>
                  <li>Programming (C#, Python, Web)</li>
                  <li>Database (UML, MySQL, PostgreSQL, OLAP)</li>
                  <li>Statistic (PowerBI, Talend)</li>
                  <li>Mathematics (TOMIC)</li>
                  <li>Project management</li>
                </ul>
              </div>
            </v-timeline-item>

            <v-timeline-item size="x-small" dot-color="rgb(9, 99, 114)">
              <div>
                CESI Engineering School (<b>2019 - 2021</b>)
              </div>
              <div>
                <b>Integrated preparatory cycle with IT option</b>
                <ul style="margin-left: 20px">
                  <li>Science (Physics, Mathematics)</li>
                  <li>Basic programming</li>
                  <li>Database</li>
                </ul>
              </div>
            </v-timeline-item>

            <v-timeline-item size="x-small" dot-color="rgb(9, 99, 114)">
              <div>
                Marc Bloch High School (<b>2019</b>)
              </div>
              <div>
                <b>Scientist degree with Physics option</b>
              </div>
            </v-timeline-item>
          </v-timeline>
        </v-col>
      </v-col>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "Studies"
}
</script>

<style scoped>

</style>