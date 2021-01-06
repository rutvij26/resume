<template>
<div class="Sec">
  <Education />
  <Work />
</div>
</template>

<script>
import Education from './Education';
import Work from './Work.vue';
export default {
  name:'home',
  components: {
    Education,
    Work
  }
};
</script>

<style>
.Sec{
  display: -webkit-inline-box;
}
</style>