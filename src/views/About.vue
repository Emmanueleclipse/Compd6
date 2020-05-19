<template>
  <q-page class="about text-white">
    <!-- Section 1 -->
    <div class="hero row justify-center items-center bg-secondary ">
      <div class="q-pl-sm  col-md-10 col-sm-11 col-11 row h1 ">
        <div class="col-xl-11 col-12">
          WE ARE <strong>SIMPLIFYING</strong> THE STRUCTURED SETTLEMENT
          FACTORING INDUSTRY BY
          <strong>DIRECTLY CONNECTING POLICY HOLDERS TO INVESTORS.</strong>
        </div>
      </div>
    </div>
    <!-- Section 2  -->
    <div class="row bg-primary justify-center items-center section ">
      <div class="q-pl-sm col-11 col-md-10 row">
        <div class="col-md-7 col-lg-6  q-pt-md ">
          <div class="row">
            <div class="col-11 col-md-10 sec2-h1">
              The current process is slow, painful and outdated.
            </div>
          </div>
          <br />
          <div class="row">
            <div class="col-12 col-md-10">
              <p class="sec2-p">
                Both policy holders and investors are losing time and money
                because of this.
              </p>
            </div>
          </div>
          <div class="row">
            <div class="sec2-img col-md-9 col-lg-11 gt-sm">
              <q-img :src="require('@/assets/undrawMemoryStorage.png')"></q-img>
            </div>
            <div class="col-11 lt-md q-my-lg ">
              <q-img :src="require('@/assets/undrawMemoryStorage.png')"></q-img>
            </div>
          </div>
        </div>
        <div class="col-1 gt-md "></div>
        <div class="col-md-5 col-12 row ">
          <div class="col-12 gt-sm">
            <q-img :src="require('@/assets/timeline1.png')"> </q-img>
          </div>
          <div class="col-12 lt-md">
            <q-img :src="require('@/assets/MobileTimeline.png')"> </q-img>
          </div>
        </div>
      </div>
    </div>
    <!-- section 3  -->
    <div class="row bg-secondary justify-center items-center section  ">
      <div class="row">
        <div class="col-12">
          <div class="q-pt-md text-center">
            <div class="row  justify-center">
              <div class="col-10 sec2-h1 gt-sm">
                Our automated process.
              </div>
              <div class="col-10 sec2-h1 lt-md text-left">
                Our automated process.
              </div>
            </div>
            <br />
            <div class="row justify-center ">
              <div class="col-5 gt-sm ">
                <p class="sec2-p">
                  Our technology enables us to automate parts of the process
                  which, in turn means it’s much fast, more cost effective and
                  better for everyone.
                </p>
              </div>
              <div class="col-10 lt-md ">
                <p class="sec2-p" style="text-align:left">
                  Our technology enables us to automate parts of the process
                  which, in turn means it’s much fast, more cost effective and
                  better for everyone.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-11">
        <div class="row  justify-center q-pt-xl">
          <div class="col-11 q-px-lg gt-sm">
            <q-img :src="require('@/assets/process.png')"> </q-img>
          </div>
          <div class="col-11 lt-md ">
            <q-img :src="require('@/assets/MobileProcess.png')"> </q-img>
          </div>
        </div>
      </div>
      <div class="col-12">
        <div class="row q-mt-lg q-pt-lg justify-center ">
          <div class="col-12 text-center q-gutter-lg">
            <q-btn
              :to="CreateAccount"
              size="lg"
              color="white"
              text-color="primary"
              class="text-weight-bold  q-px-lg"
              style="border-radius:10px; letter-spacing:0px  "
            >
              sign up
            </q-btn>
            <q-btn
              :to="LearnMore"
              style="background-color: rgba(0,0,0,0.2) ; border-radius:10px;"
              text-color="white"
              flat
              class="q-py-sm text-weight-bold q-px-md "
            >
              <q-icon left name="mdi-information"></q-icon> LEARN MORE</q-btn
            >
          </div>
        </div>
      </div>
    </div>
    <!-- section 4 -->
    <div class="row bg-positive section justify-center  ">
      <!-- Founders Text  -->
      <div class="col-md-5 col-11">
        <div class="row  q-pl-sm">
          <div class="col-12">
            <div class="sec2-h1">
              The founders.
            </div>
            <br />
            <div class="row">
              <div class="col-lg-8 col-md-11 col-12">
                <p class="sec2-p ">
                  Our mission statement is simple:
                  <br />
                  <br />
                  <strong>
                    WE ARE SIMPLIFYING THE STRUCTURED SETTLEMENT FACTORING
                    INDUSTRY BY DIRECTLY CONNECTING POLICY HOLDERS TO
                    INVESTORS.</strong
                  >
                  <br />
                  <br />
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                  do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodo consequat. Duis aute
                  irure dolor in reprehenderit in voluptate velit esse cillum.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Founders List -->
      <div class="col-md-5 col-12">
        <div class="row">
          <div class="col-12">
            <q-list>
              <q-item class="q-px-none items-start">
                <q-avatar size="10em">
                  <q-img :src="require('@/assets/F1.png')"></q-img>
                </q-avatar>
                <div class="row">
                  <div class="col-12 self-center founder-name q-pt-sm">
                    Robert Biscardi
                  </div>
                  <div class="col-lg-8 col-12 founder-dec">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut.
                  </div>
                </div>
              </q-item>
              <q-item class="q-px-none items-start">
                <q-avatar size="10em">
                  <q-img :src="require('@/assets/F2.png')"></q-img>
                </q-avatar>
                <div class="row">
                  <div class="col-12 self-center founder-name q-pt-sm">
                    Jan Tadehsz Strezelecki
                  </div>
                  <div class="col-lg-8 col-12 founder-dec">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut.
                  </div>
                </div>
              </q-item>
              <q-item class="q-px-none items-start">
                <q-avatar size="10em">
                  <q-img :src="require('@/assets/F3.png')"></q-img>
                </q-avatar>
                <div class="row">
                  <div class="col-12 self-center founder-name q-pt-sm">
                    Justin Savory
                  </div>
                  <div class="col-lg-8 col-12 founder-dec">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut.
                  </div>
                </div>
              </q-item>
            </q-list>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <!-- About Section  -->
      <div class="col section row bg-primary col-12 col-md-6 ">
        <div class="col col-12">
          <div class="row justify-center">
            <div class="col col-11 col-md-8 ">
              <div class="row">
                <div class="col col-4 q-mb-lg">
                  <q-img :src="require('@/assets/aboutlogo.png')"> </q-img>
                </div>
              </div>
              <div class="row q-pa-sm  ">
                <div class="col col-lg-8 col-10  EndTitle ">
                  Get started today.
                </div>
              </div>
              <div class="row q-ml-sm">
                <div class="col col-11 col-md-10 col-sm-8 EndDec">
                  Nulla venenatis scelerisque tincidunt. Aenean accumsan quis
                  velit sit amet tincidunt. Cras nunc libero, volutpat et ante
                  eu, luctus semper felis.
                </div>
              </div>
              <div class="row q-ml-sm">
                <div class="col q-pt-lg ">
                  <q-btn
                    :to="CreateAccount"
                    text-color="primary"
                    color="white"
                    class=" text-weight-bold EndBtn"
                    >SIGN UP</q-btn
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- Help Section  -->
      <div class="col section row bg-secondary col-12 col-md-6 ">
        <div class="col col-12">
          <div class="row justify-center">
            <div class="col col-11 col-md-8 ">
              <div class="row">
                <div class="col row col-5 col-md-7">
                  <div class="col col-7">
                    <q-img :src="require('@/assets/help.png')"> </q-img>
                  </div>
                </div>
              </div>
              <div class="row q-py-sm ">
                <div class="col col-lg-8 col-md-10 EndTitle ">
                  Help and support.
                </div>
              </div>
              <div class="row">
                <div class="col col-11 col-md-10 col-sm-8 EndDec">
                  Nulla venenatis scelerisque tincidunt. Aenean accumsan quis
                  velit sit amet tincidunt. Cras nunc libero, volutpat et ante
                  eu, luctus semper felis.
                </div>
              </div>
              <div class="row">
                <div class="col q-pt-lg ">
                  <q-btn
                    :to="support"
                    text-color="primary"
                    color="white"
                    class=" text-weight-bold EndBtn"
                    >CONTACT SUPPORT</q-btn
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
export default {
  data: () => ({
    CreateAccount: "#",
    LearnMore: "#",
    support: "#"
  })
};
</script>

<style>
.h1 {
  font-size: 80px;
  line-height: 82px;
}
.section {
  padding-top: 6% !important;
  padding-bottom: 6% !important ;
}
.sec2-h1 {
  font-size: 40px;
  font-weight: bold;
  line-height: 48px;
}
.sec2-p {
  font-weight: 200;
  font-size: 20px;
}
.sec2-img {
  position: relative;
  margin-top: 5em;
  margin-bottom: -15rem !important ;
}
.founder-name {
  font-size: 24px;
  font-weight: 400;
}
.founder-dec {
  font-size: 16px;
  font-weight: 300;
}
@media only screen and (min-device-width: 319px) and (max-device-width: 426px) {
  .hero {
    margin: 0 !important;
    padding: 0 !important;
    padding-bottom: 10% !important ;
    padding-top: 10% !important ;
  }
  .h1 {
    font-size: 32px;
    line-height: 36px;
  }
  .sec2-img {
    margin-top: 2em;
    margin-bottom: 1em !important ;
  }
  .sec2-h1 {
    font-size: 24px;
    line-height: 32px;
  }
}
@media only screen and (min-device-width: 427px) and (max-device-width: 768px) {
  .h1 {
    font-size: 4em;
    line-height: 1em;
  }
  .sec2-img {
    margin-top: 2em;
    margin-bottom: 1em !important ;
  }
}
@media only screen and (min-device-width: 769px) and (max-device-width: 1024px) {
  .h1 {
    font-size: 4em;
    line-height: 1.2em;
  }
  .sec2-img {
    margin-top: 2em;
    margin-bottom: -11rem !important ;
  }
  .sec2-h1 {
    font-size: 30px;
  }
  .sec2-p {
    font-weight: 200;
    font-size: 18px;
  }
}
</style>
