<template lang="">
  <div class="header">
    <div class="header__container">
      <div class="logo">Air</div>
      <Nav />
      <a href="#" class="header__hire">HIRE US</a>
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
.header {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1;
  color: #fff;
}
.header__container {
  display: flex;
  justify-content: space-between;
  padding: 30px 0 30px 0;
  max-width: 1200px;
  margin: 0 auto;
}

.logo {
  font-size: 35px;
}

.header__hire {
  margin-bottom: 0;
}

.header__hire {
  text-decoration: none;
  color: #fff;
  font-size: 13px;
  font-weight: 600;
  letter-spacing: 2px;
}

.header__hire:hover {
  border-bottom: 2px solid #ff9c8e;
}
</style>
