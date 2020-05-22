<template>
  <q-layout class="compd" view="hHh lpR fFf">
    <q-header reveal class="bg-white q-pa-md">
      <q-toolbar class="margin">
        <a href="/">
          <img class="logo" contain src="@/assets/logo.png" />
        </a>
        <q-space></q-space>
        <div class="btns" v-for="btns in links" :key="btns.name">
          <q-btn
            text-color="primary"
            class="btn gt-sm text-weight-bold q-mr-xs btn-shrink"
            flat
            :to="btns.link"
            >{{ btns.name }}
          </q-btn>
        </div>
        <q-btn
          :to="signuup"
          text-color="primary"
          flat
          style="border-radius:8px;"
          class=" gt-sm q-ml-sm btn bg-grey-12 text-weight-bold btn-shrink"
          >SIGN UP
        </q-btn>

        <q-btn
          class="q-ml-sm"
          type="a"
          target="_blank"
          :href="appleBtn"
          flat
          dense
        >
          <img class="applebtn" src="@/assets/appStore.png" />
        </q-btn>

        <q-btn
          color="primary"
          dense
          flat
          round
          icon="menu"
          class="lt-md"
          @click="right = !right"
        />
      </q-toolbar>
    </q-header>

    <q-drawer v-model="right" side="right" overlay behavior="mobile" elevated>
      <q-list class="q-py-lg q-px-sm">
        <q-item
          clickable
          v-ripple
          v-for="btns in links"
          :key="btns.name"
          exact
          :to="btns.link"
        >
          <q-item-section class="text-weight-bold">
            {{ btns.name | UpCase }}
          </q-item-section>
        </q-item>
        <q-item clickable v-ripple exact :to="signuup">
          <q-item-section class="text-weight-bold">
            {{ "Sign up" | UpCase }}
          </q-item-section>
        </q-item>
      </q-list>
    </q-drawer>

    <q-page-container>
      <router-view />
    </q-page-container>

    <footer class="bg-white ">
      <q-toolbar class="row justify-center  footer-padding ">
        <div class="row col-12 justify-around ">
          <div class="col col-md-3 col-11 q-mb-sm ">
            <img height="36px" contain src="@/assets/logo.png" />
            <div class="footer-text">
              99 Wall St #4000, New York, NY 10005
            </div>
          </div>
          <div class="col col-md-5 col-12 q-mb-sm">
            <div class="row text-center items-center btnRow">
              <div class="col col-12 q-gutter-md ">
                <q-btn type="a" target="_blank" :href="appleBtn" flat dense>
                  <img class="" src="@/assets/appStore.png" />
                </q-btn>
                <q-btn
                  :to="signuup"
                  text-color="primary"
                  flat
                  style="border-radius:8px;"
                  class="btn bg-grey-12 text-weight-bold"
                  >login or sign up
                </q-btn>
              </div>
              <div class=" footer-text  col col-12 ">
                Terms of service • Privacy Policy • © COMPD PTY LTD 2019
              </div>
            </div>
          </div>
          <div class="col col-md-3 col-11 q-mb-sm">
            <div>
              <q-card
                style="border-radius:10px"
                class="q-pa-md shadow-0 bg-grey-12"
              >
                <q-item class="row justify-center">
                  <q-item-section avatar>
                    <q-avatar square>
                      <img src="@/assets/helpicon.png" />
                    </q-avatar>
                  </q-item-section>
                  <q-item-section class="col-11">
                    <div
                      style="font-size:14px"
                      class=" text-primary text-weight-bold"
                    >
                      Have some feedback for us? Feel free to
                      <a href="">get in touch.</a>
                    </div>
                  </q-item-section>
                </q-item>
              </q-card>
            </div>
          </div>
        </div>
      </q-toolbar>
    </footer>
  </q-layout>
</template>

<script>
export default {
  name: "App",
  components: {},

  data: () => ({
    right: false,
    links: [
      { name: "home", link: "/" },
      { name: "about us", link: "about" },
      { name: "support", link: "#" }
    ],
    signuup: "#",
    appleBtn: "#"
  }),
  filters: {
    UpCase(value) {
      return value.toUpperCase();
    }
  }
};
</script>
<style>
.compd,
body {
  font-family: "Barlow", sans-serif !important;
}
.btn {
  font-size: 14px;
}
.margin {
  padding-left: 8.7% !important;
  padding-right: 7.5% !important;
}
.logo {
  height: 36px;
}
.footer-padding {
  padding-left: 7% !important;
  padding-right: 7.5% !important;
  margin-top: 3%;
  margin-bottom: 1%;
}
.footer-text {
  font-size: 12px !important;
  font-weight: 600 !important;
  margin-top: 1rem;
  color: #273156;
}
@media only screen and (max-device-width: 769px) {
  .footer-padding,
  .margin {
    padding-left: 1% !important;
    padding-right: 1% !important;
  }
  .footer-padding {
    margin-top: 10%;
  }
}
@media only screen and (min-device-width: 319px) and (max-device-width: 550px) {
  .applebtn {
    height: 25px;
  }
  .logo {
    width: auto;
    height: 22px;
  }
}
@media only screen and (max-device-width: 768px) {
  .btnRow {
    text-align: left !important;
    padding-left: 2em;
  }
}
@media only screen and (max-device-width: 426px) {
  .btnRow {
    padding-left: 1em;
  }
}
@media only screen and (max-device-width: 321px) {
  .btnRow {
    padding-left: 0.5em;
  }
}
</style>
