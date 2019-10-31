<template>
  <Footer class="pt-5">
    <div class="container py-3 px-0">
      <div class="row pb-4 footer-links mb-3">
        <div class="col-12 col-lg-3">
          <ul class="nav flex-column">
            <li class="nav-item"><a href="" class="nav-link">Site Map</a></li>
            <li class="nav-item">
              <a href="" class="nav-link">Terms and Condition</a>
            </li>
            <li class="nav-item">
              <a href="" class="nav-link">Privacy Policy</a>
            </li>
            <li class="nav-item"><a href="" class="nav-link">Help</a></li>
            <li class="nav-item"><a href="" class="nav-link">Affiliate</a></li>
          </ul>
        </div>
        <div class="col-12 col-lg-3">
          <ul class="nav flex-column">
            <li class="nav-item">
              <a href="" class="nav-link">Our Location</a>
            </li>
            <li class="nav-item">
              <a href="" class="nav-link">Career</a>
            </li>
            <li class="nav-item">
              <a href="" class="nav-link">About</a>
            </li>
            <li class="nav-item"><a href="" class="nav-link">Contact</a></li>
          </ul>
        </div>
        <div class="col-12 col-lg-3">
          <ul class="nav flex-column">
            <li class="nav-item"><a href="" class="nav-link">FAQs</a></li>
            <li class="nav-item">
              <a href="" class="nav-link">Blog</a>
            </li>
            <li class="nav-item">
              <a href="" class="nav-link">Car Blog</a>
            </li>
            <li class="nav-item"><a href="" class="nav-link">Location</a></li>
            <li class="nav-item"><a href="" class="nav-link">Press</a></li>
          </ul>
        </div>
        <div class="col-12 col-lg-3 subscribe">
          <p>Sign up to get our newsletter</p>
          <form action="" class="form-inline">
            <div class="input-group">
              <input
                type="email"
                name="email"
                placeholder="Your email... "
                class="form-control-plaintext"
              />
            </div>
          </form>
        </div>
      </div>
      <div class="w-100 d-flex justify-content-end">
        <ul class="nav">
          <li class="nav-item">
            <a href="" class="nav-link"
              ><img src="/images/png/fill-3.png" class="img-fluid" alt=""
            /></a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link"
              ><img src="/images/png/fill-1.png" class="img-fluid" alt=""
            /></a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link"
              ><img src="/images/png/group-7.png" class="img-fluid" alt=""
            /></a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link"
              ><img src="/images/png/fill-33.png" class="img-fluid" alt=""
            /></a>
          </li>
          <li class="nav-item">
            <a href="" class="nav-link"
              ><img src="/images/png/fill-23.png" class="img-fluid" alt=""
            /></a>
          </li>
        </ul>
      </div>
    </div>
  </Footer>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>

<style lang="scss">
footer {
  border: solid 0.1px #979797;
  background-color: #211f20;
  .footer-links {
    border-bottom: solid 1px #9b9b9b;
    .nav {
      font-family: 'Source Sans Pro';
      a {
        color: #9b9b9b;
        letter-spacing: 0.39px;
        font: {
          size: 0.875rem;
        }
      }
    }
    .subscribe {
      p {
        color: #9b9b9b;
      }
      input {
        background-color: transparent;
        border-bottom: solid 0.1px #979797;
      }
    }
  }
}
</style>
