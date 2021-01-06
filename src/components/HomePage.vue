<template>
<div>
<section class="Sec">
  <Education />
  <Work />
</section>
<section class="Sec">
<Projects />
</section>
</div>
</template>

<script>
import Education from "./Cards/Education";
import Work from "./Cards/Work.vue";
import Projects from "./Cards/Projects.vue";
export default {
  name: "home",
  components: {
    Education,
    Work,
    Projects,
  },
};
</script>

<style>
.Sec {
  display: -webkit-inline-box;
}
</style>