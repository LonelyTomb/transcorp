<template>
  <section class="pt-7 pb-5 min-vh-100 about-component" id="about">
    <h2 class="text-center text-uppercase">About Us</h2>
    <div class="container-fluid text-center">
      <div class="row mt-5">
        <p class="mx-auto col-auto col-lg-5 about-desc-header">
          A best place to enjoy your life
        </p>
      </div>
      <div class="row mt-6">
        <p class="mx-auto col-auto col-lg-5 about-desc">
          Transcorp Hilton Hotel is situated in the heart of Nigeria’s Federal
          Capital Territory, a 40-minute drive from the Nnamdi Azikiwe
          International Airport in Abuja. It is a 670–room, 5-star hotel that
          provides luxury accommodation, exotic cuisine, and fully equipped
          meeting rooms and to business travellers and tourists from all over
          the world
        </p>
      </div>
      <img
        class="w-50 mx-auto position-relative"
        src="https://res.cloudinary.com/nazarick/image/upload/q_auto:good/v1572520763/transcorp/rectangle-7.png"
        alt="photo"
      />
    </div>
    <div
      class="photos w-100 position-relative text-center d-flex flex-column mt-5 pb-5"
    >
      <a href="" class="mb-5">VIEW MORE PHOTOS</a>
    </div>
  </section>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style lang="scss">
.about-component {
  h2 {
    letter-spacing: 4.94px;
    color: #9b9b9b;
    font: {
      family: 'Source Sans Pro';
      size: 0.975rem;
    }
  }
  .about-desc-header {
    font-family: Georgia;
    font-size: 3.325rem;
  }
  .about-desc {
    color: #9b9b9b;
    family: 'Source Sans Pro';
    letter-spacing: 0.82px;
    size: 0.975rem;
  }
  .container-fluid {
    & > img {
      bottom: -150px;
      z-index: 1;
    }
  }
  .photos {
    min-height: 200px;
    background: {
      image: url('https://res.cloudinary.com/nazarick/image/upload/q_auto:good/v1572520834/transcorp/rectangle-11.png');
      repeat: no-repeat;
      size: cover;
    }
    a {
      margin-top: 150px;
      color: #9b9b9b;
      letter-spacing: 4.94px;
      font: {
        size: 0.875rem;
      }
    }
  }
}
</style>
