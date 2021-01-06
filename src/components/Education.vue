<template>
  <div>
    <div class="education">
        
      <v-card elevation="24">
        <v-card-title>EDUCATION</v-card-title>
        
        <div class="cards">
        <v-card-subtitle>
          <div class="subcard">
            <v-card elevation="24">
              <v-card-title
                >VishwaKarma Institute of Information Technology</v-card-title>
              <v-card-text>
               <spam> Bachelor of Engineering in Information Technology, <br>06/2016-06/2020, CGPA:7.81</spam></v-card-text>
            </v-card>
          </div>
          <section class="ji">
          <div class="subcard">
            <v-card elevation="24">
              <v-card-title
                >HSC</v-card-title>
              <v-card-text>Percentage : 73.4%</v-card-text>
            </v-card>
          </div>
          <div class="subcard">
            <v-card elevation="24">
              <v-card-title
                >SSC</v-card-title>
              <v-card-text>Percentage : 89.8%</v-card-text>
            </v-card>
          </div>
          </section>
        </v-card-subtitle>
        </div>
      </v-card>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.education {
  /* border-style: double; */
  margin: 20px;
  max-width:440px;
  font-weight: bold;
  font-size: 100px;
}

.cards {
  text-decoration-color: black;
  justify-content:space-evenly;
  /* display: inline-block; */
 
}

.subcard {
  margin: 10px;
  width: auto;
  max-width: fit-content;
  padding-bottom: 20px;
  display: inline-block;
}

</style>