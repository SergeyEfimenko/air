<template>
  <div class="footer">
    <div class="footer__container">
      <div class="logo">Air</div>
      <Nav />
    </div>
  </div>
</template>

<script>
import Nav from '@/components/Nav';
export default {
  components: {
    Nav,
  },
};
</script>

<style>
.footer {
  width: 100%;
  background-color: #0289ff;
  color: #fff;
}

.footer__container {
  display: flex;
  justify-content: space-between;
  padding: 30px 0 30px 0;
  max-width: 1200px;
  margin: 0 auto;
}

.logo {
  font-size: 35px;
}
</style>
