<template>
  <q-page class="Home text-white">
    <!-- Section: Hero -->
    <div class="hero row justify-center items-center bg-secondary text-white">
      <div class="col row col-xl-6 col-lg-4 col-md-6  col-12">
        <div
          style="font-size:40px;"
          class="hero-text col text-bold q-pt-lg q-px-lg col-xl-8 col-md-12 col-lg-12 col-sm-8 col-xs-10"
        >
          Quickly turn your future payments into cash.
        </div>
        <div style="font-size:20px" class=" row text-weight-thin q-pa-lg  ">
          <div class="col-xl-7 col-xs-9 sub-text ">
            Easily submit your structured settlement, presettlement, sporting
            contract documents and receive bids almost instantly.
          </div>
        </div>
        <div class="row q-px-lg q-gutter-md ">
          <q-btn
            :to="CreateAccount"
            size="lg"
            color="white"
            text-color="primary"
            class="text-weight-bold gt-sm"
            style="border-radius:10px ;  "
          >
            sign up
          </q-btn>
          <q-btn
            color="white"
            text-color="primary"
            class="text-weight-bold q-mb-sm lt-md"
            style="border-radius:10px ; letter-spacing:-1px "
          >
            sign up
          </q-btn>
          <q-btn
            style="border-radius:10px ; border:solid white 2px;"
            size="lg"
            flat
            class="gt-sm bg-secondary btn-shrink"
          >
            <q-icon left size="md" name="mdi-information"></q-icon>
            Watch the video</q-btn
          >
        </div>
      </div>
      <div class="col col-2 lg"></div>
      <div class="banner col col-xl- col-md-4 col-sm-11 col-11">
        <q-img
          class="banner-img"
          :src="require('@/assets/video-placeholder.png')"
        ></q-img>
      </div>
    </div>
    <!-- Section:How it works -->
    <div class="section-work row bg-primary">
      <div class="col">
        <div class="row justify-center">
          <!-- Title  -->
          <div class=" title2 col col-12 text-center gt-sm">
            How it works
          </div>
          <div
            style="font-size:24px"
            class="text-weight-bold lt-md col col-11 "
          >
            How it works
          </div>
          <!-- Text -->
          <div class="row col gt-sm col-12 text-center justify-center">
            <div class="col des2 col-4 col-lg-5 col-md-7 ">
              Upload your documents and store the safely and securely on our
              platform. See which annuity documents we can store for you by
              selecting them on the wheel.
            </div>
          </div>
          <div class="row lt-md col col-12  justify-center">
            <div class="col des2 col-11 ">
              Upload your documents and store the safely and securely on our
              platform. See which annuity documents we can store for you by
              selecting them on the wheel.
            </div>
          </div>
          <div class="row col col-12 justify-center q-mt-xl q-pt-lg ">
            <div class="col col-10  gt-sm ">
              <q-img :src="require('@/assets/asset.png')"></q-img>
            </div>
            <div class="col col-11 q-mb-lg lt-md ">
              <q-img :src="require('@/assets/asset2.png')"></q-img>
            </div>
          </div>
        </div>
        <div class="card1 row lt-md justify-center">
          <div class="col col-11 ">
            <q-card class="q-my-md q-pa-md">
              <q-card-section class="q-pa-sm">
                <div
                  style="font-size:24px"
                  class=" text-weight-bold text-primary"
                >
                  How it works.
                </div>
              </q-card-section>
              <q-card-section
                style="font-size:16px"
                class="text-primary q-pa-sm "
              >
                Upload your documents and store the safely and securely on our
                platform. See which annuity documents we can store for you by
                selecting them on the wheel.
              </q-card-section>
              <q-card-actions>
                <q-btn
                  style="font-weight:600; font-size:14px; border-radius:10px; "
                  class="q-pa-xs"
                  color="secondary"
                  >SIGN UP</q-btn
                >
              </q-card-actions>
            </q-card>
          </div>
        </div>
      </div>
    </div>
    <!-- Section: More info  -->
    <div class="section row bg-secondary relative-position">
      <div class="col">
        <!-- Card2 -->
        <div class="row lt-md justify-center ">
          <div class="col col-11">
            <q-card class="bg-positive q-pa-md">
              <q-card-section class="q-pa-sm">
                <div
                  style="font-size:24px"
                  class=" text-weight-bold text-white"
                >
                  Download COMPD on the App Store or Google Play
                </div>
              </q-card-section>
              <q-card-actions>
                <q-btn
                  style="margin-left:-10px"
                  type="a"
                  target="_blank"
                  :href="AppSrore"
                  dense
                  flat
                  :ripple="false"
                  ><img class="Cbtn" src="@/assets/appStore.png" />
                </q-btn>
              </q-card-actions>
              <q-card-actions>
                <q-btn
                  style="margin-left:-10px"
                  type="a"
                  target="_blank"
                  :href="PlayStore"
                  dense
                  flat
                  :ripple="false"
                  ><img class="Cbtn" src="@/assets/playstorebtn.png" />
                </q-btn>
              </q-card-actions>
            </q-card>
          </div>
        </div>
        <!-- Cards -->
        <div class="card-row row justify-center absolute-top gt-sm">
          <div class="col  col-lg-5 col-md-5 q-mr-md">
            <q-card class=" cards text-primary q-pa-md">
              <q-card-section class="title q-pb-xs">
                Get started right now
              </q-card-section>
              <q-card-section class="row">
                <div
                  class="text-h6 text-weight-regular q-pb-xs col col-xl-7 col-lg-8"
                >
                  Create a free account today, start receiving bids directly and
                  make some money.
                </div>
              </q-card-section>
              <q-card-section class=" xl q-pa-md"></q-card-section>

              <q-card-actions>
                <q-btn
                  :to="CreateAccount"
                  style="border-radius:10px; font-size:16px"
                  color="secondary"
                  dense
                  class="q-pa-sm"
                  >CREATE AN ACCOUNT</q-btn
                >
              </q-card-actions>
            </q-card>
          </div>
          <div class="col col-lg-5 col-md-5 q-ml-md">
            <q-card class="cards bg-positive q-pa-md">
              <q-card-section class="row">
                <div class="col title col-xl-8 col-lg-9 ">
                  Download COMPD on the App Store or Google Play
                </div>
              </q-card-section>
              <q-card-section class="q-pa-lg"></q-card-section>

              <q-card-actions class="q-mt-lg">
                <q-btn
                  type="a"
                  target="_blank"
                  :href="AppSrore"
                  dense
                  flat
                  :ripple="false"
                  ><img class="Cbtn" src="@/assets/appStore.png" /> </q-btn
                ><q-btn
                  type="a"
                  target="_blank"
                  :href="PlayStore"
                  dense
                  flat
                  :ripple="false"
                  ><img class="Cbtn" src="@/assets/playstorebtn.png" />
                </q-btn>
              </q-card-actions>
            </q-card>
          </div>
        </div>
        <!-- Text-Row -->
        <div class="row Text-Row">
          <div class="col row text-white justify-center">
            <div class="col row col-md-5 col-sm-11 col-11 ">
              <div class="title">We can store your documents</div>
              <div
                style="font-size:16px;"
                class="col col-md-11 col-sm-10 col-12 q-mt-md "
              >
                Upload your documents and store the safely and securely on our
                platform. See which annuity documents we can store for you by
                selecting them on the wheel.
              </div>
            </div>
            <div class="col col-5 items-start row justify-end gt-sm">
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
        <!-- Illistration Row -->
        <div class="row justify-center gt-sm  q-mt-xl">
          <div class="col row col-6 gt-sm ">
            <div class="col col-lg-6 col-md-8  ">
              <!--<q-img
                class="injueryImg"
                :src="require('@/assets/injury.png')"
              ></q-img>-->
              <img
                class="injueryImg full-width"
                src="@/assets/injury.png"
                usemap="#imageMap"
              />
            </div>
          </div>
          <!-- Injury Card  -->
          <div class="col col-4 items-center row justify-end ">
            <q-card class="speech-bubble q-pa-lg ">
              <transition name="fade" mode="out-in">
                <div :key="selectedCircleItem.title">
                  <q-item>
                    <q-item-section avatar>
                      <q-avatar square>
                        <img
                          :src="
                            require('@/assets/wheel/' + selectedCircleItem.img)
                          "
                        />
                      </q-avatar>
                    </q-item-section>
                    <q-item-section>
                      <q-item-label class="title text-primary">
                        {{ selectedCircleItem.title }}
                      </q-item-label>
                    </q-item-section>
                  </q-item>
                  <q-card-section class="row">
                    <div class=" col col-xl-11 col-12 text-primary des2">
                      {{ selectedCircleItem.body }}
                    </div>
                  </q-card-section>
                </div>
              </transition>
            </q-card>
          </div>
        </div>
        <!-- Tablet-Mobile View -->
        <div class="row justify-center lt-md  q-pt-xl  ">
          <div class="col col-11 col-sm-8">
            <!--<q-img contain :src="require('@/assets/injury.png')"></q-img>-->
            <img
              contain
              class="full-width"
              src="@/assets/injury.png"
              usemap="#imageMapMobile"
            />
          </div>
          <div class="row justify-center full-width">
            <div class=" col col-11 ">
              <!-- injury Card -->
              <q-card class="">
                <transition name="fade" mode="out-in">
                  <div :key="selectedCircleItem.title">
                    <q-item class="q-pa-md">
                      <q-item-section>
                        <q-item-label
                          class=" Card2-title text-weight-bold text-primary"
                        >
                          {{ selectedCircleItem.title }}
                        </q-item-label>
                      </q-item-section>
                      <q-item-section avatar>
                        <q-avatar square>
                          <img
                            :src="
                              require('@/assets/wheel/' +
                                selectedCircleItem.img)
                            "
                          />
                        </q-avatar>
                      </q-item-section>
                    </q-item>
                    <q-card-section class="row q-pt-none">
                      <div class="col text-primary col-10">
                        {{ selectedCircleItem.body }}
                      </div>
                    </q-card-section>
                  </div>
                </transition>
              </q-card>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- Section: Testimonial -->
    <div class="row section section-testimonial bg-positive relative-position	">
      <q-img
        class="absolute-top-left quote "
        contain
        :src="require('@/assets/Quote.png')"
      >
      </q-img>
      <!-- desktop view  -->
      <div class="col gt-sm">
        <div class="row">
          <div class="col title text-center gt-sm ">
            What our customers are saying
          </div>
        </div>
        <!-- Carousel  -->
        <div class="row justify-center">
          <div class="col col-xl-10 q-py-xl ">
            <q-carousel
              v-model="slide"
              class="bg-transparent"
              arrows
              swipeable
              animated
              autoplay
              infinite
              transition-next="slide-left"
              transition-prev="slide-right"
            >
              <!-- slide 1  -->
              <q-carousel-slide
                class=" row justify-center items-center"
                :name="0"
              >
                <div class="row items-center justify-center q-gutter-lg ">
                  <div
                    class="col col-3"
                    v-for="item in slide1"
                    :key="item.index"
                  >
                    <q-card class="bg-transparent no-shadow q-pa-md">
                      <q-item class="row justify-center">
                        <q-item-section avatar>
                          <q-avatar size="80px">
                            <img :src="item.img" />
                          </q-avatar>
                        </q-item-section>
                      </q-item>
                      <q-item-section>
                        <div class="text-center des2">
                          {{ item.comment }}
                        </div>
                      </q-item-section>
                      <q-card-section
                        style="font-size:22px; font-weight:600;"
                        class="text-center "
                      >
                        {{ item.name }}
                      </q-card-section>
                    </q-card>
                  </div>
                </div>
              </q-carousel-slide>
              <!-- slide 2  -->
              <q-carousel-slide
                class=" row justify-center items-center"
                :name="1"
              >
                <div class="row items-center justify-center q-gutter-lg ">
                  <div
                    class="col col-3"
                    v-for="item in slide2"
                    :key="item.index"
                  >
                    <q-card class="bg-transparent no-shadow q-pa-md">
                      <q-item class="row justify-center">
                        <q-item-section avatar>
                          <q-avatar size="80px">
                            <img :src="item.img" />
                          </q-avatar>
                        </q-item-section>
                      </q-item>
                      <q-item-section>
                        <div class="text-center des2">
                          {{ item.comment }}
                        </div>
                      </q-item-section>
                      <q-card-section
                        style="font-size:22px; font-weight:600;"
                        class="text-center "
                      >
                        {{ item.name }}
                      </q-card-section>
                    </q-card>
                  </div>
                </div>
              </q-carousel-slide>
              <!-- slide 3 -->
              <q-carousel-slide
                class=" row justify-center items-center"
                :name="2"
              >
                <div class="row items-center justify-center q-gutter-lg ">
                  <div
                    class="col col-3"
                    v-for="item in slide3"
                    :key="item.index"
                  >
                    <q-card class="bg-transparent no-shadow q-pa-md">
                      <q-item class="row justify-center">
                        <q-item-section avatar>
                          <q-avatar size="80px">
                            <img :src="item.img" />
                          </q-avatar>
                        </q-item-section>
                      </q-item>
                      <q-item-section>
                        <div class="text-center des2">
                          {{ item.comment }}
                        </div>
                      </q-item-section>
                      <q-card-section
                        style="font-size:22px; font-weight:600;"
                        class="text-center "
                      >
                        {{ item.name }}
                      </q-card-section>
                    </q-card>
                  </div>
                </div>
              </q-carousel-slide>
            </q-carousel>
          </div>
        </div>
      </div>
      <!-- Mobile View  -->
      <div class="col lt-md">
        <div class="row justify-center q-mt-lg ">
          <div class="col  col-11 text-weight-bold" style="font-size:24px;">
            What our customers are saying.
          </div>
        </div>
        <div class="row justify-center ">
          <div class="col col-11">
            <q-carousel
              v-model="slide"
              class="bg-transparent "
              height="300px"
              swipeable
              animated
              infinite
              transition-next="slide-left"
              transition-prev="slide-right"
            >
              <q-carousel-slide
                :name="index"
                class=" row justify-center items-center q-px-none"
                v-for="(item, index) in MobileSlides"
                :key="index"
              >
                <q-card class="carousel-card shadow-0 q-pa-sm ">
                  <q-item>
                    <q-item-section avatar>
                      <q-avatar><img :src="item.img"/></q-avatar>
                    </q-item-section>
                    <q-item-section>
                      <q-item-label class="des2 text-weight-bold">
                        {{ item.name }}
                      </q-item-label></q-item-section
                    >
                  </q-item>
                  <q-card-section>
                    {{ item.comment }}
                  </q-card-section>
                </q-card>
              </q-carousel-slide>
            </q-carousel>
          </div>
        </div>
      </div>
    </div>
    <!-- Section: End -->
    <div class="row">
      <!-- About Section  -->
      <div class="col section row bg-primary col-12 col-md-6 ">
        <div class="col col-12">
          <div class="row justify-center">
            <div class="col col-11 col-md-8 ">
              <div class="row">
                <div class="col col-5 col-md-7">
                  <q-img :src="require('@/assets/team.png')"> </q-img>
                </div>
              </div>
              <div class="row q-pa-sm ">
                <div class="col col-8 EndTitle ">
                  About Us
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
                    text-color="primary"
                    color="white"
                    class=" text-weight-bold EndBtn"
                    >LEARN MORE ABOUT COMPD</q-btn
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
              <div class="row q-pa-sm ">
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
    <map name="imageMap">
      <area
        v-for="(item, index) in injuryCircleItems"
        :key="index"
        shape="circle"
        :coords="item.coords.join(',')"
        @mouseover="selectInjuryCircle(index)"
        style="cursor: pointer;"
      />
    </map>
    <map name="imageMapMobile">
      <area
        v-for="(item, index) in injuryCircleItems"
        :key="index"
        shape="circle"
        :coords="item.coords.join(',')"
        @mouseover="selectInjuryCircle(index)"
        style="cursor: pointer;"
      />
    </map>
  </q-page>
</template>

<script>
import imageMapResize from "image-map-resizer";

export default {
  name: "Home",
  components: {},
  created() {
    this.selectedCircleItem = this.injuryCircleItems[0].content;
  },
  mounted() {
    imageMapResize();
  },
  methods: {
    selectInjuryCircle(item) {
      this.selectedCircleItem = this.injuryCircleItems[item].content;
    }
  },
  data: () => ({
    selectedCircleItem: null,
    injuryCircleItems: [
      {
        coords: [650, 260, 80], // x, y, radius
        content: {
          title: "I have a personal injury",
          body: `Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
          do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
          laboris nisi ut aliquip ex ea commodo consequat.`,
          img: "1.png"
        }
      },
      {
        coords: [650, 577, 80], // x, y, radius
        content: {
          title: "Title 2",
          body: "Body 2",
          img: "2.png"
        }
      },
      {
        coords: [381, 719, 80], // x, y, radius
        content: {
          title: "Title 3",
          body: "Body 3",
          img: "5.png"
        }
      },
      {
        coords: [112, 577, 80], // x, y, radius
        content: {
          title: "Title 4",
          body: "Body 4",
          img: "4.png"
        }
      },
      {
        coords: [112, 260, 80], // x, y, radius
        content: {
          title: "Title 5",
          body: "Body 5",
          img: "2.png"
        }
      },
      {
        coords: [381, 104, 80], // x, y, radius
        content: {
          title: "Title 6",
          body: `Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
          do eiusmod tempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam, quis nostrud exercitation ullamco
          laboris nisi ut aliquip ex ea commodo consequat.`,
          img: "3.png"
        }
      }
    ],
    //Button Links
    AppSrore: "https://google.com",
    PlayStore: "#",
    CreateAccount: "#",
    LearnMore: "#",
    slide: 0,
    slide1: [
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 1"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 1"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 1"
      }
    ],
    slide2: [
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 2"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 2"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 2"
      }
    ],
    slide3: [
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 3"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 3"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last 3"
      }
    ],
    MobileSlides: [
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last"
      },
      {
        img: "https://cdn.quasar.dev/img/avatar2.jpg",
        comment:
          "“Nulla venenatis scelerisque tincidunt. Aeneanaccumsan quis velit sit amet tincidunt. Cras nunclibero, volutpat et ante eu, luctus semper felis.",
        name: "First Last"
      }
    ]
  })
};
</script>

<style>
.hero,
.section,
.section-work {
  padding-top: 6% !important;
  padding-bottom: 6% !important ;
}
.banner-img {
  height: 315px;
}
.title2 {
  font-size: 32px;
  font-weight: bold;
  letter-spacing: 1px;
}
.des2 {
  font-size: 16px;
}
.title {
  font-size: 32px !important;
  font-weight: bold !important;
}
.card-row {
  margin-top: -10rem !important;
}

.Cbtn {
  height: 50px;
}
.section-work {
  padding-bottom: 15% !important;
}
.cards {
  height: 300px;
}
.Text-Row {
  margin-top: 5%;
}
.speech-bubble {
  width: 660px;
  height: 300px;
  border-radius: 10px !important;
  padding: 10px;
  position: relative;
}
.speech-bubble::after {
  content: "";
  display: block;
  position: absolute;
  width: 0;
  height: 0;
  top: 8rem;
  left: -1.5rem;
  border-top: 1.5rem solid transparent;
  border-bottom: 1.5rem solid transparent;
  border-right: 2rem solid white;
}
.Card2-title {
  font-size: 20px;
}
.carousel-card {
  background-color: rgba(0, 0, 0, 0.2) !important;
}
.quote {
  width: 10% !important;
  top: 10% !important;
  left: 10% !important;
}
/* End section */
.EndBtn {
  border-radius: 10px !important;
  letter-spacing: 1pt !important;
  padding: 0.5rem !important;
}
.EndTitle {
  font-size: 32px !important;
  font-weight: bold;
}
.EndDec {
  font-size: 22px !important;
}

@media only screen and (min-device-width: 427px) and (max-device-width: 768px) {
  .banner {
    margin-top: 5% !important ;
  }
  .section-work {
    padding-bottom: 3% !important ;
  }
}
@media only screen and (min-device-width: 319px) and (max-device-width: 426px) {
  .hero {
    margin: 0 !important;
    padding: 0 !important;
    padding-bottom: 10% !important ;
    padding-top: 10% !important ;
  }
  .hero-text {
    margin: 0 !important;
    padding-top: 0 !important;
    font-size: 24px !important;
  }
  .sub-text {
    margin: 0 !important;
    padding-top: 0 !important;
    font-size: 16px !important;
  }
  .banner {
    margin-top: 10% !important ;
  }
  .title {
    font-size: 24px !important;
    font-weight: bold !important;
  }
  .section-work {
    padding-bottom: 2% !important ;
    padding-top: 15% !important ;
  }
  .Card2-title {
    font-size: 16px;
  }
  .EndTitle {
    font-size: 24px !important;
  }
  .EndDec {
    font-size: 16px !important;
    font-weight: lighter;
  }
  .EndBtn {
    border-radius: 10px !important;
    font-size: 14px !important;
    letter-spacing: 0pt !important;
    padding: 0.2rem !important;
  }
}
@media only screen and (min-device-width: 769px) and (max-device-width: 1024px) {
  .title {
    font-size: 25px !important;
  }
  .card-row {
    margin-top: -7rem !important;
  }
  .cards {
    height: 270px;
  }
  .Text-Row {
    margin-top: 15%;
  }
  .speech-bubble {
    height: 320px;
  }
}

@media only screen and (min-device-width: 1025px) {
  .cards {
    height: 300px;
  }
  .Text-Row {
    margin-top: 10%;
  }
}
@media only screen and (max-device-width: 768px) {
  .quote {
    width: 50% !important;
    top: 5% !important;
    left: 5% !important;
  }
}

/* Animations */

/* Fade */
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.3s;
}
.fade-enter,
.fade-leave-to {
  opacity: 0;
}

/* Shrink */
@keyframes push {
  50% {
    transform: scale(0.9);
  }
}
.btn-shrink:hover {
  animation: push 0.3s linear 1;
}
</style>
