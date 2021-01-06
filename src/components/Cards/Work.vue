<template>
  <div>
    <div class="education">
      <v-card elevation="10">
        <v-card-title><strong>WORK EXPERIENCE</strong></v-card-title>

        <div class="cards">
          <v-card-subtitle>
            <div class="subcard">
              <v-card elevation="10">
                <v-card-title
                  ><strong>Full Stack Developer Intern</strong>
                  BOP Consultancy And Services</v-card-title
                >
                <v-card-text>
                  <spam> </spam>06/2019 – 07/2019 <br />
                  -Represented web team at meetings with executives and
                  discussed project goals and milestones <br />-Developed
                  landing pages, dashboards and online applications using Visual
                  Studio Code , MongoDb Database and Vue scripting<br />-Designed,
                  implemented and monitored web pages and sites for continuous
                  improvement<br />-Researched new technologies, software
                  packages for use in website projects</v-card-text
                >
              </v-card>
            <!-- </div>

            <div class="subcard"> -->
              <v-card elevation="10">
                <v-card-title
                  >Web Developer Intern<br />Dev Infotech</v-card-title
                >
                <v-card-text>
                  <spam> </spam>06/2018 – 12/2018 <br />
                  -Created site layout and user interface using HTML and CSS
                  practices <br />-Pitched in to assist senior developers to
                  meet pressing deadlines during under-staffed periods<br />-Tested
                  websites and performed troubleshooting prior to
                  deployment</v-card-text
                >
              </v-card>
            </div>
          </v-card-subtitle>
        </div>
      </v-card>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.education {
  /* border-style: double; */
  margin: 20px;
  max-width: 880px;
  font-weight: bold;
  font-size: 100px;
  display: flex;
}

.cards {
  text-decoration-color: black;
  justify-content: space-evenly;
  display: -webkit-inline-box;
  justify-content: space-between;
}

.subcard {
  margin: 10px;
  width: auto;
  max-width: fit-content;
  padding-bottom: 20px;
  display: -webkit-inline-box;
}

</style>