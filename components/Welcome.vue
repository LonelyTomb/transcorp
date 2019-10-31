<template>
  <section class="w-100 welcome-component min-vh-100">
    <div class="position-relative">
      <video
        id="welcome-video"
        class="w-100 position-absolute h-100"
        autoplay
        muted
        loop
        poster=""
      />
      <div
        class="welcome-block text-center min-vh-100 d-flex justify-content-center flex-column w-100"
      >
        <div class="welcome-text">
          <p class="text-capitalize">Welcome To</p>
          <p>Transcorp Hotel</p>
          <p>A place to experience and enjoy the life</p>
          <img
            src="/images/png/ic-play-circle-outline.png"
            alt="play image"
            class="img-fluid"
          />
        </div>
      </div>
      <div class="checkin-block position-absolute w-100">
        <div class="w-75 mx-auto shadow-lg">
          <div class="row d-flex flex-column flex-lg-row">
            <div class="col-auto col-lg-3 checkin-box p-4">
              <p class="checkin-user-type my-0">CHECK-IN</p>
              <div class="d-flex justify-content-between align-items-end">
                <p class="my-0 px-0">
                  <span class="day px-2">24</span>
                  <span class="month">/JUNE</span>
                </p>
                <span class="p-2">
                  <img
                    src="/images/svg/arrow-down-sign-to-navigate.svg"
                    class="img-fluid down-arrow"
                    alt=""
                /></span>
              </div>
            </div>
            <div class="col-auto col-lg-3 checkout-box p-4">
              <p class="checkin-user-type my-0">CHECK-OUT</p>
              <div class="d-flex justify-content-between align-items-end">
                <p class="my-0 px-0">
                  <span class="day px-2">24</span>
                  <span class="month">/JUNE</span>
                </p>
                <span class="p-2">
                  <img
                    src="/images/svg/arrow-down-sign-to-navigate.svg"
                    class="img-fluid down-arrow"
                    alt=""
                /></span>
              </div>
            </div>
            <div class="col-auto col-lg-3 guest-box p-4">
              <p class="checkin-user-type my-0">GUEST</p>
              <div class="d-flex justify-content-between align-items-end">
                <p class="my-0 px-0">
                  <span class="day px-2">03</span>
                </p>
                <span class="p-2">
                  <img
                    src="/images/svg/arrow-down-sign-to-navigate.svg"
                    class="img-fluid down-arrow"
                    alt=""
                /></span>
              </div>
            </div>
            <div class="col-auto col-lg-3 promo-box py-4">
              <div class="container d-flex flex-column justify-content-center">
                <div class="text-center py-2">
                  <p>Have a promotional code ?</p>
                  <button class="btn btn-block p-2">CHECK AVAILABILITY</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Welcome'
}
</script>

<style scoped lang="scss">
.welcome-component {
  video {
    z-index: -1;
    background: transparent
      url('https://res.cloudinary.com/nazarick/image/upload/q_75/v1572520759/transcorp/rectangle-3.png')
      no-repeat 0 0;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
  }
  .welcome-block {
    color: #fff;
    background: {
      image: linear-gradient(
        to bottom,
        rgba(0, 0, 0, 0.7),
        rgba(67, 67, 67, 0.2)
      );
    }
    p {
      &:nth-child(1) {
        letter-spacing: 4.94px;
        font: {
          size: 0.975em;
          weight: bold;
        }
      }
      &:nth-child(2) {
        font: {
          size: 3.35rem;
          family: Georgia;
        }
        letter-spacing: 3.06px;
      }
      &:nth-child(3) {
        letter-spacing: 0.82px;
        font: {
          size: 0.975em;
          weight: 600;
        }
      }
    }
  }
  .checkin-block {
    bottom: -80px;
    z-index: -1;
    .row {
      background-color: #ffffff;
      & > div {
        &:nth-child(-n + 3) {
          border: {
            right: solid thin #ebebf2;
          }
        }
      }
    }
    .checkin-box,
    .checkout-box,
    .guest-box {
      .checkin-user-type {
        color: #9b9b9b;
        letter-spacing: 0.58px;
        font: {
          size: 0.9rem;
        }
      }
      .day {
        font: {
          family: Georgia;
          size: 3.1rem;
        }
      }
      .month {
        letter-spacing: 0.58px;
        font: {
          size: 0.975rem;
        }
      }
    }

    .promo-box {
      background-color: #053b58;
      color: #fff;
      p {
        font: {
          size: 0.975rem;
        }
      }
      button {
        background-color: #ff7200;
        letter-spacing: 0.58px;
        font: {
          size: 0.875rem;
        }
        border-radius: 0;
        color: #fff;
      }
    }
  }
}
</style>
