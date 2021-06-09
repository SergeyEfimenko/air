<template>
  <div class="information">
    <div class="information__container">
      <div class="information__massage">
        <form class="information__form" action="#">
          <div class="information__form-title">Send us a massage</div>
          <input name="email" required placeholder="Your mail" type="email" />
          <input name="name" required placeholder="Your name" type="text" />
          <input
            name="massage"
            required
            placeholder="Your message"
            type="text"
          />
          <a href="#" class="btn">Send</a>
        </form>
      </div>
      <div class="information__contact">
        <div class="information__contact-title">Contact us</div>
        <div class="information__contact-block">
          <p class="information__contact-call-subtitle">CALL US</p>
          <p class="information__contact-call-info">654 321 987</p>
        </div>
        <div class="information__contact-block">
          <p class="information__contact-call-subtitle">VISIT US</p>
          <p class="information__contact-call-info">
            2905 West Drive, Buffalo Glove
          </p>
        </div>
        <div class="information__contact-block">
          <p class="information__contact-call-subtitle">OUR SOCIAL</p>
          <div>
            <a href="#"
              ><img class="social__icon" src="../images/facebook.svg" alt="fb"
            /></a>
            <a href="#"
              ><img class="social__icon" src="../images/twitter.svg" alt="tw"
            /></a>
            <a href="#"
              ><img
                class="social__icon"
                src="../images/instagram.svg"
                alt="inst"
            /></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.information {
  padding: 100px 0;
  background-color: #0289ff;
  border-radius: 0 14% 0 0;
  color: #fff;
}
.information__container {
  max-width: 1200px;
  margin: 0 auto;
  width: 100%;
  display: flex;
}
.information__massage {
  margin-top: 100px;
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 300px;
  margin: 0 auto;
}

.information__form-title {
  font-size: 30px;
  font-weight: 900;
  padding-bottom: 30px;
}

.information__form input {
  height: 50px;
  margin-bottom: 15px;
  background-color: inherit;
  padding: 0 20px;
  font-size: 14px;
  font-weight: 300px;
  border: none;
  border-bottom: 1px solid #fff;
  width: 100%;
  padding-left: 0;
}
.information__form input::placeholder {
  color: #bedcff;
  font-weight: 700;
}

.information__form input:nth-child(3) {
  margin-bottom: 20px;
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
}

.information__contact {
  margin-top: 100px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  width: 300px;
  margin: 0 auto;
}

.information__contact-title {
  font-size: 30px;
  font-weight: 900;
  padding-bottom: 35px;
}

.information__contact-call-subtitle {
  font-size: 13px;
  font-weight: 900;
  color: #92c4ff;
  letter-spacing: 2px;
}

.information__contact-call-info {
  font-size: 20px;
  font-weight: 700;
}

.social__icon {
  height: 25px;
  width: 25px;
  margin-right: 40px;
}
</style>
