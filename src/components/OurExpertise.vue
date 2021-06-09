<template>
  <div class="ourexpertise">
    <div class="ourexpertise__container">
      <h3 class="ourexpertise__title">Our expertise</h3>
      <OurExpertiseBlocks />
    </div>
  </div>
</template>

<script>
import OurExpertiseBlocks from '@/components/OurExpertiseBlocks';
export default {
  components: {
    OurExpertiseBlocks,
  },
};
</script>
<style>
.ourexpertise {
  background-color: #fff;
  height: 100vh;
}

.ourexpertise__container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 40px 0;
}
.ourexpertise__title {
  text-align: center;
  font-size: 50px;
  font-weight: bold;
  color: #253757;
}
</style>
