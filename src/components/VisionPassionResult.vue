<template>
  <div class="job">
    <div class="job__container">
      <div class="job__content">
        <h2 class="job__content-title">Vision, Passion, Result</h2>
        <p class="job__content-text">
          We are sure first-rate job is possible only if all three components
          are united.
        </p>
        <a href="#" class="btn">Apply</a>
      </div>
    </div>
  </div>
</template>

<style>
.job {
  height: 100vh;
  background-color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  position: relative;
  background-image: url(../images/example.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}

.job__container {
  z-index: 1;
}

.job__content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  width: 500px;
  margin: 0 auto;
}

.job__content-title {
  color: #253757;
  font-weight: 900;
  font-size: 45px;
}

.job__content-text {
  font-size: 20px;
  color: #6b788a;
  line-height: 1.4;
  font-weight: 700;
  padding-bottom: 50px;
}

.btn {
  display: block;
  width: 240px;
  text-align: center;
  height: 50px;
  line-height: 50px;
  color: #fff;
  background-color: pink;
  border-radius: 25px;
  border: none;
  text-decoration: none;
}
</style>
