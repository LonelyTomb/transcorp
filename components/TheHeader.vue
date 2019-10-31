<template>
  <Header class="container w-75">
    <div class="row">
      <p
        class="p-1 border-bottom w-100 top-header-message d-flex justify-content-between align-content-center"
      >
        <span
          >Contact us directly at 01 33943 +234 807 340 4890 ( Local time 12: 00
          )</span
        >
        <span
          class="lang-dropdown dropdown-toggle"
          data-toggle="dropdown"
          aria-haspopup="true"
          aria-expanded="false"
          >EN
          <!--          <img-->
          <!--            src="/images/svg/arrow-down-sign-to-navigate.svg"-->
          <!--            alt="Down Arrow"-->
          <!--        />-->
        </span>
      </p>
      <nav class="navbar w-100">
        <ul
          class="nav d-flex w-100 justify-content-between align-content-center text-uppercase p-3"
        >
          <li class="nav-item d-none d-lg-block">
            <a href="#home" class="nav-link" @click.prevent="">Home</a>
          </li>
          <li class="nav-item d-none d-lg-block">
            <a href="#about" class="nav-link" @click.prevent="">About Us</a>
          </li>
          <li class="nav-item d-none d-lg-block">
            <a href="#rooms" class="nav-link" @click.prevent="">Our Rooms</a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link p-0"
              ><img src="/images/png/transcorp-1.png" alt="transcorp logo"
            /></a>
          </li>
          <li class="nav-item d-none d-lg-block">
            <a href="#reservations" class="nav-link" @click.prevent=""
              >Reservation</a
            >
          </li>
          <li class="nav-item d-none d-lg-block">
            <a href="#blog" class="nav-link" @click.prevent="">Blog</a>
          </li>
          <li class="nav-item d-none ">
            <a href="#contact" class="nav-link" @click.prevent="">Contact</a>
          </li>
        </ul>
      </nav>
    </div>
  </Header>
</template>

<script>
export default {
  name: 'TheHeader',
  methods: {}
}
</script>

<style lang="scss">
header {
  color: #526173;
  font-family: 'Source Sans Pro';

  .top-header-message {
    font: {
      size: 0.85rem;
    }

    .lang-dropdown {
      img {
        width: 16px;
        height: auto;
      }
    }
  }
  nav {
    .nav-link {
      color: #526173;
      letter-spacing: 0.58px;
      font: {
        size: 0.975rem;
      }
    }
  }
}
</style>
