<template>
  <div class="create">
    <img class="create__img" src="../images/approach.png" alt="" />
    <div class="create__container">
      <div class="create__bg"></div>
      <div class="create__content">
        <p class="create__content-text">Approach</p>
        <h3 class="create__content-title">
          We strive to create meaningful projects
        </h3>
        <div class="creative__content-info">
          <div class="creative__content-info-block">
            <div class="creative__content-info-block-img">
              <img src="../images/speaker.svg" alt="" />
            </div>
            <div class="creative__content-info-block-text">
              We are sure thatthe brandsbuild ona strong strategy, big ideas and
              simple human values alweys win. Only such brand change the game.
            </div>
          </div>
          <div class="creative__content-info-block">
            <div class="creative__content-info-block-img">
              <img src="../images/calendar.svg" alt="" />
            </div>
            <div class="creative__content-info-block-text">
              No one can realize the idea as its creatiors. Therefore, we set
              upagency-based photoand video production departments.
            </div>
          </div>
          <div class="creative__content-info-block">
            <div class="creative__content-info-block-img">
              <img src="../images/calendar.svg" alt="" />
            </div>
            <div class="creative__content-info-block-text">
              We strive to create meaningful project that make brands
              valuable,and the worldaround us more aesthetic.
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.create {
  color: #fff;
  display: flex;
  align-items: center;
  overflow: hidden;
  position: relative;
}

.create__container {
  display: flex;
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
  position: relative;
}

.create__img {
  position: absolute;
  bottom: 0;
  right: 0;
  z-index: 1;
  height: 70%;
}

.create__bg {
  position: absolute;
  top: 0px;
  left: -20px;
  width: 100vw;
  height: 100%;
  background-color: #ff9c8e;
  color: #fff;
  border-radius: 14% 0 0 14%;
}

.create__content {
  min-height: 800px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  width: 400px;
  position: relative;
  z-index: 1;
  margin-left: 150px;
}

.create__content-text {
  font-weight: 700;
  font-size: 14px;
  letter-spacing: 1px;
}

.create__content-title {
  font-size: 30px;
  font-weight: 900;
  letter-spacing: 2px;
  line-height: 1.5;
}

.creative__content-info-block {
  display: flex;
  margin: 25px;
  padding-bottom: 25px;
}

.creative__content-info-block-text {
  line-height: 1.3;
}

.creative__content-info-block-img {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  background-color: #fff;
  width: 50px;
  text-align: center;
  height: 50px;
  line-height: 50px;
  color: #fff;
  border-radius: 50%;
  margin-right: 20px;
}
</style>
