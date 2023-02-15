<template>
  <v-container>
    <v-card>
      <v-col cols="12">
        <v-row>
          <v-card-title style="text-decoration: underline; font-size: 22px;">
            <b>Realisations</b>
          </v-card-title>
        </v-row>

        <v-row>
          <v-col cols="6">
            <v-card-text>
              Scholar projects
            </v-card-text>

            <v-carousel show-arrows="hover" hide-delimiters progress="primary">
              <v-dialog>
                <template v-slot:activator="{ props }">
                  <v-carousel-item src="https://moodle-ingenieurs.cesi.fr/pluginfile.php/390146/course/overviewfiles/A3-Info_Stockage_880x560.jpg" cover v-bind="props">
                    <v-sheet height="15%">
                      <div class="d-flex fill-height justify-center align-center">
                        <div class="text-h3">
                          Big Data
                        </div>
                      </div>
                    </v-sheet>
                  </v-carousel-item>
                </template>

                <template v-slot:default="{ isActiveData }">
                  <v-card>
                    <v-toolbar color="primary" title="Big Data"></v-toolbar>

                    <v-card-text>
                      The goal is to fulfill the needs and requirements of access and analysis of the users.
                      <br>
                      Firstly, we had to analyze the architecture to implement and to design the data model.
                      <br>
                      After that, we had to collect data from different sources (PostgreSQL, CSV, etc...) with Talend and centralize them in an Hive store.
                      <br>
                      Then, with PowerBI, we had to create different Dashboards to display statistics and help the users to make an analysis.
                    </v-card-text>
                  </v-card>
                </template>
              </v-dialog>

              <v-dialog>
                <template v-slot:activator="{ props }">
                  <v-carousel-item src="https://moodle-ingenieurs.cesi.fr/pluginfile.php/390143/course/overviewfiles/A3-Info_ProgSyst_880x560.jpg" cover v-bind="props">
                    <v-sheet height="15%">
                      <div class="d-flex fill-height justify-center align-center">
                        <div class="text-h3">
                          Programming
                        </div>
                      </div>
                    </v-sheet>
                  </v-carousel-item>
                </template>

                <template v-slot:default="{ isActiveProg }">
                  <v-card>
                    <v-toolbar color="primary" title="Programming"></v-toolbar>

                    <v-card-text>
                      The objective of this project is to make an application that allow its users to create Saves (full or differential) and that generate logs.
                      <br>
                      To start, we had to prepare a Git with versioning and to make diagrams that describes how the application will work.
                      <br>
                      Then, we had to develop the application using C# and a WPF graphical interface. We also had to implement multithreading in order to pause or continue a save and show progression without blocking the UI.
                    </v-card-text>
                  </v-card>
                </template>
              </v-dialog>

              <v-dialog>
                <template v-slot:activator="{ props }">
                  <v-carousel-item src="https://moodle-ingenieurs.cesi.fr/pluginfile.php/390149/course/overviewfiles/A3-Info_AdminSI_880x560.jpg" cover v-bind="props">
                    <v-sheet height="15%">
                      <div class="d-flex fill-height justify-center align-center">
                        <div class="text-h3">
                          System Administration
                        </div>
                      </div>
                    </v-sheet>
                  </v-carousel-item>
                </template>

                <template v-slot:default="{ isActiveSystem }">
                  <v-card>
                    <v-toolbar color="primary" title="System Administration"></v-toolbar>

                    <v-card-text>
                      This project aimed to merge Information System of 2 companies and add security.
                      <br>
                      We had to establish the new infrastructure of the IS and the associated migration process.
                      <br>
                      Then, we had to configure security with VPN, DMZ and Firewalls.
                      <br>
                      Finally, we had to make a mockup of the new IS.
                    </v-card-text>
                  </v-card>
                </template>
              </v-dialog>
            </v-carousel>
          </v-col>

          <v-col cols="6">
            <v-card-text>
              Professional projects
            </v-card-text>

            <v-carousel show-arrows="hover" hide-delimiters progress="success">
              <v-dialog>
                <template v-slot:activator="{ props }">
                  <v-carousel-item src="https://www.processmaker.com/wp-content/uploads/2020/12/process-mining-vs-business-intelligence.jpg" cover v-bind="props">
                    <v-sheet height="15%">
                      <div class="d-flex fill-height justify-center align-center">
                        <div class="text-h3">
                          Business Intelligence
                        </div>
                      </div>
                    </v-sheet>
                  </v-carousel-item>
                </template>

                <template v-slot:default="{ isActivePro }">
                  <v-card>
                    <v-toolbar color="primary" title="Business Intelligence"></v-toolbar>

                    <v-card-text>
                      This project aimed to update the BI tool, actually, the former BI Tool works with Navision but ERLAB choose to migrate on Odoo.
                      <br>
                      I had to gather the project specification with the Directors.
                      <br>
                      One the specifications was done, I used Laravel Framework to help me building a cube with all the necessary datas.
                      <br>
                      Finally, I've made all the Dashboards that were asked by the users and then, I had to show them how to use Metabase if they want to create custom Dashboards.
                    </v-card-text>
                  </v-card>
                </template>
              </v-dialog>

              <v-dialog>
                <template v-slot:activator="{ props }">
                  <v-carousel-item src="https://www.processmaker.com/wp-content/uploads/2020/12/process-mining-vs-business-intelligence.jpg" cover v-bind="props">
                    <v-sheet height="15%">
                      <div class="d-flex fill-height justify-center align-center">
                        <div class="text-h3">
                          Intranet
                        </div>
                      </div>
                    </v-sheet>
                  </v-carousel-item>
                </template>

                <template v-slot:default="{ isActivePro }">
                  <v-card>
                    <v-toolbar color="primary" title="Intranet"></v-toolbar>

                    <v-card-text>
                      This project aimed to update the BI tool, actually, the former BI Tool works with Navision but ERLAB choose to migrate on Odoo.
                      <br>
                      I had to gather the project specification with the Directors.
                      <br>
                      One the specifications was done, I used Laravel Framework to help me building a cube with all the necessary datas.
                      <br>
                      Finally, I've made all the Dashboards that were asked by the users and then, I had to show them how to use Metabase if they want to create custom Dashboards.
                    </v-card-text>
                  </v-card>
                </template>
              </v-dialog>
            </v-carousel>
          </v-col>
        </v-row>
      </v-col>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: "Realisations"
}
</script>

<style scoped>

</style>