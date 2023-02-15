<template>
  <v-container>
    <v-card>
      <v-col cols="12">
        <v-row>
          <v-card-title style="text-decoration: underline; font-size: 22px">
            <b>Professional Experiences</b>
          </v-card-title>
        </v-row>

        <v-col>
          <v-timeline density="compact">
            <v-timeline-item size="x-small" dot-color="rgb(211, 112, 11)">
              <div>
                ERLAB DFS <b>October 2021 - Now</b>
              </div>
              <div>
                <b>IT Engineer in sandwich curses</b>
                <ul style="margin-left: 20px">
                  <li>Build specifications with users</li>
                  <li>Project modelization and management</li>
                  <li>Developping and testing the solution</li>
                </ul>
              </div>
            </v-timeline-item>

            <v-timeline-item size="x-small" dot-color="rgb(211, 112, 11)">
              <div>
                ERLAB DFS <b>April 2021 - July 2021</b>
              </div>
              <div>
                <b>Laravel Developper</b>
                <ul style="margin-left: 20px">
                  <li>Gather needs</li>
                  <li>Redesign the BI tool</li>
                  <li>Statistics & dashboards</li>
                </ul>
              </div>
            </v-timeline-item>

            <v-timeline-item size="x-small" dot-color="rgb(211, 112, 11)">
              <div>
                ERLAB DFS <b>August 2021</b>
              </div>
              <div>
                <b>Telephone operator & Receptionist</b>
                <ul style="margin-left: 20px">
                  <li>Answer phone calls from clients</li>
                  <li>Welcome visitors</li>
                  <li>Mail postage</li>
                </ul>
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
  name: "Experiences"
}
</script>

<style scoped>

</style>