<template>
  <div class="col-12 success pa-md-16 main-page">
    <div class="row ma-0">
      <div class="col-12 col-sm-6 col-lg-7">
        <div class="title-text">
          <h1 class="white--text">کـــــاروان</h1>
          <br>
          <h2 class="white--text">
            همسفر لحظه های پربار
          </h2>
        </div>
        <div class="my-16">
          <div>
            <v-btn rounded color="lightSuccess" class="" to="/learn-reservation">
              مشاهده آموزش رزور کردن
            </v-btn>
          </div>
          <div class="mt-3">
            <v-btn rounded color="lightSuccess" class="white" to="/learn-check-in">
              مشاهده آموزش درخواست حاضری
            </v-btn>
          </div>
          <div class="mt-3">
            <v-btn rounded color="lightSuccess" class="" to="/learn-turn-in">
              مشاهده آموزش درخواست نوبت درجا
            </v-btn>
          </div>
        </div>
        <div class="row ma-0 sub-text">
          <div class="col-12 col-md-6 d-flex logo">
            <img src="/Frame.png">
            <p class="white--text mr-3">امکان نصب و بروزرسانی اپلیکیشن کاروان در کافه بازار و وبسایت کاروان فراهم می باشد.</p>
          </div>
          <div class="col-12 col-md-6 pr-md-16">
            <p class="white--text mb-0">
              <v-icon small class="white--text">mdi-phone</v-icon>
              09100354770
            </p>
            <p>
              <v-icon small class="white--text mb-0">mdi-web</v-icon>
              <a href="https://carvann.ir/" class="white--text">www.carvann.ir</a>
            </p>
          </div>
        </div>
      </div>
      <div class="col-12 col-sm-6 col-lg-5">
        <img src="/hazeri-img.png">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "index",
  layout: 'default'
}
</script>

