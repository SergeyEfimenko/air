<template>
  <div class="ourexpertise__list">
    <div class="ourexpertise__list-inner">
      <div class="ourexpertise__list-item">
        <img
          class="ourexpertise__list-item-image"
          src="../images/branding.png"
          alt="branding"
        />
        <h4 class="ourexpertise__list-item-title">Branding</h4>
        <p class="ourexpertise__list-item-text">
          We create additional value for companies, products, services as well
          as verbal and visual ways to deliver it to the audience.
        </p>
      </div>
      <div class="ourexpertise__list-item">
        <img
          class="ourexpertise__list-item-image"
          src="../images/communication.png"
          alt="communication"
        />
        <h4 class="ourexpertise__list-item-title">Communication</h4>
        <p class="ourexpertise__list-item-text">
          We strive to create communications that can increase media perfomance.
          We use everything - words, meanings, stories, art, movies.
        </p>
      </div>
      <div class="ourexpertise__list-item">
        <img
          class="ourexpertise__list-item-image"
          src="../images/strategy.png"
          alt="strategy"
        />
        <h4 class="ourexpertise__list-item-title">Strategy</h4>
        <p class="ourexpertise__list-item-text">
          We create business growth strategies, from the movement of its birth
          to the achievement of the necessary business indicators.
        </p>
      </div>
    </div>
  </div>
</template>

<style>
.ourexpertise__list {
  margin: 0 auto;
}

.ourexpertise__list-inner {
  display: flex;
  justify-content: space-around;
  margin: 0 -80px;
}

.ourexpertise__list-item-image {
  border-radius: 30px;
}

.ourexpertise__list-item-title {
  font-weight: bold;
  font-size: 25px;
  color: #253757;
  line-height: 0;
}

.ourexpertise__list-item-text {
  font-weight: 400;
  font-size: 15px;
  line-height: 1.5;
  color: #6b788a;
}

.ourexpertise__list-item {
  max-width: 33%;
  text-align: center;
  padding: 0 80px;
}
</style>
