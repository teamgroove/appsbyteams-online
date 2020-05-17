<template>
  <div>
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

    <div class="how-section1">
      <div class="row">
        <div class="col-md-6 how-img">
          <img
            src="https://image.ibb.co/dDW27U/Work_Section2_freelance_img1.png"
            class="rounded-circle img-fluid"
            alt=""
          />
        </div>
        <div class="col-md-6">
          <h4>Find rewarding projects</h4>
          <h4 class="subheading">
            GetLance is a great place to find more clients, and to run and grow
            your own freelance business.
          </h4>
          <p class="text-muted">
            Freedom to work on ideal projects. On GetLance, you run your own
            business and choose your own clients and projects. Just complete
            your profile and we’ll highlight ideal jobs. Also search projects,
            and respond to client invitations. Wide variety and high pay.
            Clients are now posting jobs in hundreds of skill categories, paying
            top price for great work. More and more success. The greater the
            success you have on projects, the more likely you are to get hired
            by clients that use GetLance.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6">
          <h4>Get hired quickly</h4>
          <h4 class="subheading">
            GetLance makes it easy to connect with clients and begin doing great
            work.
          </h4>
          <p class="text-muted">
            Streamlined hiring. GetLance’s sophisticated algorithms highlight
            projects you’re a great fit for. Top Rated and Rising Talent
            programs. Enjoy higher visibility with the added status of
            prestigious programs. Do substantial work with top clients. GetLance
            pricing encourages freelancers to use GetLance for repeat
            relationships with their clients.
          </p>
        </div>
        <div class="col-md-6 how-img">
          <img
            src="https://image.ibb.co/cHgKnU/Work_Section2_freelance_img2.png"
            class="rounded-circle img-fluid"
            alt=""
          />
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 how-img">
          <img
            src="https://image.ibb.co/ctSLu9/Work_Section2_freelance_img3.png"
            class="rounded-circle img-fluid"
            alt=""
          />
        </div>
        <div class="col-md-6">
          <h4>Work efficiently, effectively.</h4>
          <h4 class="subheading">
            With GetLance, you have the freedom and flexibility to control when,
            where, and how you work. Each project includes an online workspace
            shared by you and your client, allowing you to:
          </h4>
          <p class="text-muted">
            Send and receive files. Deliver digital assets in a secure
            environment. Share feedback in real time. Use GetLance Messages to
            communicate via text, chat, or video. Use our mobile app. Many
            features can be accessed on your mobile phone when on the go.
          </p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6">
          <h4>Get paid on time</h4>
          <h4 class="subheading">
            All projects include GetLance Payment Protection — helping ensure
            that you get paid for all work successfully completed through the
            freelancing website.
          </h4>
          <p class="text-muted">
            All invoices and payments happen through GetLance. Count on a simple
            and streamlined process. Hourly and fixed-price projects. For hourly
            work, submit timesheets through GetLance. For fixed-price jobs, set
            milestones and funds are released via GetLance escrow features.
            Multiple payment options. Choose a payment method that works best
            for you, from direct deposit or PayPal to wire transfer and more.
          </p>
        </div>
        <div class="col-md-6 how-img">
          <img
            src="https://image.ibb.co/gQ9iE9/Work_Section2_freelance_img4.png"
            class="rounded-circle img-fluid"
            alt=""
          />
        </div>
      </div>
    </div>
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
.how-section1 {
  margin-top: -15%;
  padding: 10%;
}
.how-section1 h4 {
  color: #ffa500;
  font-weight: bold;
  font-size: 30px;
}
.how-section1 .subheading {
  color: #3931af;
  font-size: 20px;
}
.how-section1 .row {
  margin-top: 10%;
}
.how-img {
  text-align: center;
}
.how-img img {
  width: 40%;
}
</style>
