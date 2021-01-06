<template>
  <div>
    <div class="education">
      <v-card elevation="10">
        <v-card-title>PROJECTS</v-card-title>

        <div class="cards">
          <v-card-subtitle>
            <div class="subcard">
              <v-card elevation="10">
                <v-card-title
                  >Car Rental Application (12/2018 – 04/2019)</v-card-title
                >
                <v-card-text>
                  <spam
                    >-Created a working full stack application.<br />-Used
                    netbeans software and mysql database<br />-Created complete
                    admin side software.</spam
                  ></v-card-text
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
  max-width: 440px;
  font-weight: bold;
  font-size: 100px;
}

.cards {
  text-decoration-color: black;
  justify-content: space-evenly;
  /* display: inline-block; */
}

.subcard {
  margin: 10px;
  width: auto;
  max-width: auto;
  padding-bottom: 20px;
  display: -webkit-inline-box;
}
</style>