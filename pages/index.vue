<template>
  <div>
    <logo />
    <h1 class="title">Yo. ql. Nuxt.js & Netlify CMS Starter</h1>

    <header id="header-3" class="soft-scroll header-3" data-pg-collapsed>
      <nav>
        <div class="container">
          <div
            class="col-md-8 col-md-offset-2 col-sm-8 col-sm-offset-2 col-xs-8 col-xs-offset-2"
          >
            <nav class="pull">
              <ul class="top-nav">
                <li>
                  <a href="#"
                    >Home
                    <span class="indicator"
                      ><i class="fa fa-angle-right"></i></span
                  ></a>
                </li>
                <li>
                  <a href="#"
                    >Features
                    <span class="indicator"
                      ><i class="fa fa-angle-right"></i></span
                  ></a>
                </li>
                <li>
                  <a href="#"
                    >Pages
                    <span class="indicator"
                      ><i class="fa fa-angle-right"></i></span
                  ></a>
                </li>
                <li>
                  <a href="#"
                    >Portfolio
                    <span class="indicator"
                      ><i class="fa fa-angle-right"></i></span
                  ></a>
                </li>
                <li>
                  <a href="#"
                    >Team
                    <span class="indicator"
                      ><i class="fa fa-angle-right"></i></span
                  ></a>
                </li>
                <li>
                  <a href="#"
                    >Contact
                    <span class="indicator"
                      ><i class="fa fa-angle-right"></i></span
                  ></a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
        <!-- /.container-fluid -->
      </nav>
      <!-- /.nav -->
      <section class="hero">
        <div class="container">
          <div class="brand">
            <a href="#">
              <img
                src="images/brand/pgblocks-logo-nostrap.png"
                class="brand-img img-responsive"
              />
            </a>
          </div>
          <div class="navicon" data-pg-collapsed>
            <a id="nav-toggle" class="nav-slide-btn" href="#"><span></span></a>
          </div>
          <div class="col-md-8 col-md-offset-2 text-center" data-pg-collapsed>
            <h1>rocket</h1>
            <p class="lead">
              Use a page-builder to speed up your page-creation process.
            </p>
            <a
              href="#"
              class="btn btn-info btn-block"
              style="display: inline !important;"
              >Find out more</a
            >
            <a
              href="#"
              class="btn btn-success btn-block"
              style="display: inline !important;"
              >Login</a
            >
          </div>
        </div>
      </section>
    </header>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  head() {
    return {
      script: [
        { src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }
      ]
    }
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: bold;
  font-size: 3.2rem;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 2rem;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
a {
  font-weight: bold;
  color: #526488;
}
.deploy-button {
  margin-top: 1rem;
}
</style>
