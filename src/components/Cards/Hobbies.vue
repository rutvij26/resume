<template>
  <div>
    <div class="education">
      <v-card elevation="10">
        <v-card-title>HOBBIES</v-card-title>

        <div class="cards">
          <v-card-subtitle>
            <div class="subcard1">
              <v-card elevation="10">
               <v-card-title>Gaming</v-card-title>
              </v-card>
                <v-card elevation="10">
               <v-card-title>Bike Riding</v-card-title>
              </v-card>
            </div>
            <div class="subcard1">
                <v-card elevation="10">
               <v-card-title>Puzzle Solving</v-card-title>
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