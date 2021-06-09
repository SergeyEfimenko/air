<template>
  <div class="testimonials">
    <div class="testimonials__container">
      <div class="testimonials__subtitle">TESTIMONIALS</div>
      <div class="testimonials__title">
        What<br />
        people say
      </div>

      <div class="testimonials__cards">
        <div class="testimonials__card testimonials__card--blue">
          <div class="testimonials__card-ava">
            <img src="../images/people1.jpg" alt="" />
          </div>
          <div class="testimonials__card-quotes">
            <img src="../images/quotes-blue.png" alt="" />
          </div>
          <div class="testimonials__card-text">
            AIR's ideas refreshing and out of the box. Authentic team that
            focuses on the important path of the brand.
          </div>
          <div class="testimonials__card-title">
            Tal Gilad
          </div>
          <div class="testimonials__card-post">
            Tach for America
          </div>
        </div>
        <div class="testimonials__card testimonials__card--yellow">
          <div class="testimonials__card-ava">
            <img src="../images/people2.jpg" alt="" />
          </div>
          <div class="testimonials__card-quotes">
            <img src="../images/quotes-yellow.png" alt="" />
          </div>
          <div class="testimonials__card-text">
            AIR is an exceptional that leads with creative talent, first-class
            account servicing.
          </div>
          <div class="testimonials__card-title">
            Azadeh Hawkins
          </div>
          <div class="testimonials__card-post">
            Hawkins Consulting
          </div>
        </div>
        <div class="testimonials__card testimonials__card--red">
          <div class="testimonials__card-ava">
            <img src="../images/people3.jpg" alt="" />
          </div>
          <div class="testimonials__card-quotes">
            <img src="../images/quotes-red.png" alt="" />
          </div>
          <div class="testimonials__card-text">
            AIR ralses the agency bar to stratospheric heights on both creative
            output and client service.
          </div>
          <div class="testimonials__card-title">
            Michel Grover
          </div>
          <div class="testimonials__card-post">
            Hulu
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.testimonials {
  padding: 150px 0;
}

.testimonials__container {
  max-width: 1200px;
  margin: 0 auto;
}

.testimonials__subtitle {
  color: #bfcdd7;
  font-size: 15px;
  font-weight: bold;
  line-height: 1;
  margin-bottom: 15px;
}

.testimonials__title {
  font-size: 33px;
  font-weight: bold;
  color: #253757;
  line-height: 1.2;
  padding-bottom: 100px;
}

.testimonials__cards {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
}

.testimonials__card {
  background-color: #fff;
  border-radius: 20px;
  padding: 30px;
  max-width: 300px;
}

.testimonials__card-ava {
  position: relative;
  margin-bottom: 60px;
  padding-top: 10px;
}

.testimonials__card-ava img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  z-index: 1;
  position: relative;
  display: block;
  margin: 0 auto;
}

.testimonials__card-quotes {
  display: flex;
  justify-content: center;
  text-align: center;
  padding: 0 0 20px 0;
}

.testimonials__card-ava::before {
  content: '';
  position: absolute;
  top: 21px;
  left: 16px;
  width: 112px;
  height: 46px;
  border-radius: 25px;
  transform: rotate(-60deg);
}

.testimonials__card-ava::after {
  content: '';
  position: absolute;
  bottom: 5px;
  right: 16px;
  width: 112px;
  height: 46px;
  border-radius: 25px;
  transform: rotate(-60deg);
}

.testimonials__card--blue .testimonials__card-ava::before {
  background-color: #56cdf2;
}

.testimonials__card--blue .testimonials__card-ava::after {
  background-color: #56cdf2;
}

.testimonials__card--yellow .testimonials__card-ava::before {
  background-color: #fcc306;
}

.testimonials__card--yellow .testimonials__card-ava::after {
  background-color: #fcc306;
}
.testimonials__card--red .testimonials__card-ava::before {
  background-color: #f25656;
}

.testimonials__card--red .testimonials__card-ava::after {
  background-color: #f25656;
}

.testimonials__card-text {
  padding-top: 10px;
  font-size: 14px;
  font-size: 400;
  line-height: 1.4;
  color: #6b788a;
  text-align: center;
}

.testimonials__card-title {
  font-size: 15px;
  font-weight: 700;
  text-align: center;
  color: #253757;
  padding-top: 25px;
}

.testimonials__card-post {
  color: #bfcdd7;
  font-size: 14px;
  font-weight: 900;
  text-align: center;
  padding-top: 10px;
  line-height: 1.3;
  letter-spacing: 3px;
}
</style>
