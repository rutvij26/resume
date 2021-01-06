<template>
<div>
<section class="Sec">
  <Education />
  <Projects />
  <Skill />
</section>
<section class="Sec">
  <Work />
</section>
</div>
</template>

<script>
import Education from "./Cards/Education";
import Work from "./Cards/Work.vue";
import Projects from "./Cards/Projects.vue";
import Skill from "./Cards/Skills.vue"
export default {
  name: "home",
  components: {
    Education,
    Work,
    Projects,
    Skill
  },
};
</script>

<style>
.Sec {
  display: -webkit-inline-box;
}
</style>