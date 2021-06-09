<template>
  <div class="hero">
    <div class="hero__container">
      <div class="hero__content">
        <h1 class="hero__content-title">Strategic Agency</h1>
        <p lass="hero__content-subtitle">
          We belive in the power of bold ideas thet can solve business
          challenges.
        </p>
        <a href="#" class="btn">Learn more</a>
      </div>
      <div class="hero__slider">
        <div class="hero__slider-item">
          <img
            class="hero__slider-item-image"
            src="../images/stairs.d61c5274.png"
          />
          <div class="hero__slider-item-container">
            <div class="hero__slider-btns">
              <button class="left">
                <img src="../images/button-left.svg" alt="" />
              </button>
              <button class="right">
                <img src="../images/button-right.svg" alt="" />
              </button>
            </div>
            <div class="hero__slider-item-text">
              <div class="hero__slider-title">INTRO</div>
              <div class="hero__slider-text">
                By the same illusion which lifts thehorizon.
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.hero {
  background-color: #008aff;
  color: #fff;
  border-radius: 0 0 0 14%;
  padding: 50px 0;
  height: 800px;

  display: flex;
  align-items: center;
  position: relative;
  overflow: hidden;
}

.hero__container {
  display: flex;
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
}
.hero__content-title {
  font-size: 52px;
  font-weight: bold;
  line-height: 1.1;
}

.hero__content-subtitle {
  font-size: 16px;
  line-height: 1.3;
  padding-bottom: 50px;
}

.hero__content {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  width: 300px;
}

.btn {
  display: block;
  width: 240px;
  text-align: center;
  height: 50px;
  line-height: 50px;
  color: #fff;
  background-color: #ff9c8e;
  border-radius: 25px;
  border: none;
  text-decoration: none;
  margin-top: 50px;
}

.hero__slider {
  position: absolute;
  bottom: -4px;
  right: 0;
}

.hero__slider-item {
  position: relative;
}

.hero__slider-item-container {
  padding: 0 0 30px 30px;
}

.hero__slider-item-container {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  display: flex;
}
.hero__slider-title {
  font-size: 16px;
  font-weight: bold;
  padding-bottom: 10px;
}

.hero__slider-btns {
  display: flex;
  align-items: center;
  margin-right: 30px;
}

button.right {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #fff;
  border: none;
  margin-left: 10px;
  cursor: pointer;
}

button.left {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #fff;
  border: none;
  cursor: pointer;
}
</style>
