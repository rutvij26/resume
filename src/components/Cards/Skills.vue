<template>
  <div>
    <div class="education">
      <v-card elevation="10">
        <v-card-title>SKILLS</v-card-title>

        <div class="cards">
          <v-card-subtitle>
            <div class="subcard1">
              <v-card elevation="10">
               <v-card-title>Creative Problem Solving</v-card-title>
              </v-card>
                <v-card elevation="10">
               <v-card-title>Excellent Time Management</v-card-title>
              </v-card>
            </div>
            <div class="subcard1">
                <v-card elevation="10">
               <v-card-title>Object Oriented Programming</v-card-title>
              </v-card>
                <v-card elevation="10">
               <v-card-title>Public Speaking</v-card-title>
              </v-card>
            </div>
            <div class="subcard">
                <v-card elevation="10">
               <v-card-title>C</v-card-title>
              </v-card>
              <v-card elevation="10">
               <v-card-title>C++</v-card-title>
              </v-card>
              <v-card elevation="10">
               <v-card-title>Js</v-card-title>
              </v-card>
              <v-card elevation="10">
               <v-card-title>Py</v-card-title>
              </v-card>
              <v-card elevation="10">
               <v-card-title>R</v-card-title>
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