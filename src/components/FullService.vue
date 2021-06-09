<template>
  <div class="service-section">
    <div class="service-section__container">
      <div class="service-section__content">
        <div class="service-section__subtitle">Process</div>
        <div class="service-section__title">
          Air is a full service creative agency
        </div>
        <div class="service-section__text">
          <p>Deep analytics strong strategy and bright creative ideas.</p>
          <p>
            We are sure that first-rate job is possible only if all three
            components are united
          </p>
        </div>
      </div>
      <div class="service-section__items">
        <div class="service-section__item service-section__item--blue">
          <div class="service-section__item-number">001</div>
          <div class="service-section__item-title">
            Brand Development Copywriting<br />
            Logo & Website Design Packaging
          </div>
          <a href="#" class="service-section__item-link">
            <span>
              <img src="../images/arrow.svg" alt="" />
            </span>
            Learn more
          </a>
        </div>
        <div class="service-section__item service-section__item--yellow">
          <div class="service-section__item-number">002</div>
          <div class="service-section__item-title">
            Content Production Graphic Design Video Production Post Production
          </div>
          <a href="#" class="service-section__item-link">
            <span>
              <img src="../images/arrow.svg" alt="" />
            </span>
            Learn more
          </a>
        </div>
        <div class="service-section__item service-section__item--green">
          <div class="service-section__item-number">003</div>
          <div class="service-section__item-title">
            Marketing Strategy Email Marketing Paid Advertising Blog Content &
            SEO
          </div>
          <a href="#" class="service-section__item-link">
            <span>
              <img src="../images/arrow.svg" alt="" />
            </span>
            Learn more
          </a>
        </div>
        <div class="service-section__item service-section__item--red">
          <div class="service-section__item-number">004</div>
          <div class="service-section__item-title">
            Digital Communications Influencer Marketing Product Placements
            Strategic Partnerships
          </div>
          <a href="#" class="service-section__item-link">
            <span>
              <img src="../images/arrow.svg" alt="" />
            </span>
            Learn more
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.service-section {
  position: relative;
  z-index: 1;
  padding: 150px 0;
  margin-bottom: -150px;
}

.service-section__container {
  max-width: 1200px;
  margin: 0 auto;
  width: 100%;
  display: flex;
}

.service-section__content {
  max-width: 300px;
  margin-right: auto;
  margin-top: 10%;
}

.service-section__subtitle {
  color: #bfcdd7;
  font-size: 15px;
  font-weight: bold;
  line-height: 1;
  margin-bottom: 15px;
}

.service-section__title {
  margin-bottom: 20px;
  font-size: 33px;
  font-weight: bold;
  color: #253757;
  line-height: 1.2;
}

.service-section__text p {
  margin-bottom: 20px;
  font-size: 15px;
  color: #6b788a;
  line-height: 1.5;
  font-weight: 400;
}

.service-section__text p:last-child {
  margin-bottom: 0;
}

.service-section__items {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  max-width: 700px;
  align-items: flex-start;
}

.service-section__item {
  background-color: #fff;
  width: 48%;
  border-radius: 20px;
  padding: 40px;
  margin-bottom: 4%;
  font-size: 15px;
  font-weight: bold;
  line-height: 1.3;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
}
.service-section__item-title {
  padding: 30px 0;
  font-size: 15px;
  font-weight: bold;
  line-height: 1.5;
  max-width: 175px;
  color: #6b788a;
}

.service-section__item-number {
  display: inline-block;
}

.service-section__item-link {
  display: flex;
  align-items: center;
  text-decoration: none;
  color: #253757;
  font-weight: bold;
  font-size: 20px;
}

.service-section__item-link span {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 15px;
}

.service-section__item--blue {
  transform: translateY(50%);
}

.service-section__item--blue .service-section__item-number {
  background-color: rgba(239, 250, 253, 0.9);
  color: #59ccf2;
  border-radius: 40% 40% 40% 40%;
  padding: 5px;
}

.service-section__item--blue .service-section__item-link span {
  background-color: #59ccf2;
}

.service-section__item--yellow .service-section__item-number {
  background-color: rgba(255, 250, 235, 0.9);
  color: #fcc91d;
  border-radius: 40% 40% 40% 40%;
  padding: 5px;
}

.service-section__item--yellow .service-section__item-link span {
  background-color: #fcc91d;
}
.service-section__item--green .service-section__item-number {
  background-color: rgba(236, 251, 238, 0.9);
  color: #12d84f;
  border-radius: 40% 40% 40% 40%;
  padding: 5px;
}

.service-section__item--green .service-section__item-link span {
  background-color: #12d84f;
}
.service-section__item--red .service-section__item-number {
  background-color: rgba(254, 239, 240, 0.9);
  color: #f36363;
  border-radius: 40% 40% 40% 40%;
  padding: 5px;
}

.service-section__item--red .service-section__item-link span {
  background-color: #f36363;
}

.service-section__item--green {
  transform: translateY(50%);
}
</style>
