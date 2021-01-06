<template>
<div>
<section class="Sec">
  <Education />
  <Projects />
  <Hob />
  
 </section>
<section class="Sec">
  
   <Skill />
   <Work />
  
</section>
</div>
</template>

<script>
import Education from "./Cards/Education";
import Work from "./Cards/Work.vue";
import Projects from "./Cards/Projects.vue";
import Skill from "./Cards/Skills.vue";
import Hob from "./Cards/Hobbies.vue";
export default {
  name: "home",
  components: {
    Education,
    Work,
    Projects,
    Skill,
    Hob
  },
};
</script>

<style>
.Sec {
  display: -webkit-inline-box;
  max-width: fit-content;

}
</style>