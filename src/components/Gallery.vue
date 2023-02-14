<template>
  <div class="block galleryBlock">
    <v-container>
      <h2 class="text-center">ภาพประทับใจ</h2>
      <v-row>
        <v-col v-for="item in items" :key="item.id" class="d-flex child-flex" cols="6" sm="4">
          <v-card flat tile class="d-flex">
            <v-img :src="item.src" aspect-ratio="1" class="grey lighten-2">
              <template v-slot:placeholder>
                <v-row class="fill-height ma-0" align="center" justify="center">
                  <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                </v-row>
              </template>
            </v-img>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  name: "Gallery",
  data() {
    return {
      items: [
        {
          id: 1,
          src: require("../assets/images/img1.jpeg")
        },
        {
          id: 2,
          src: require("../assets/images/img2.jpg")
        },
        {
          id: 3,
          src: require("../assets/images/img3.jpg")
        },
        {
          id: 4,
          src: require("../assets/images/img4.jpg")
        },
        {
          id: 5,
          src: require("../assets/images/img5.jpg")
        },
        {
          id: 6,
          src: require("../assets/images/img6.jpg")
        },
        {
          id: 7,
          src: require("../assets/images/img7.jpg")
        },
        {
          id: 8,
          src: require("../assets/images/img8.jpg")
        },
        {
          id: 9,
          src: require("../assets/images/img9.jpg")
        },
        {
          id: 10,
          src: require("../assets/images/img10.jpg")
        },
        {
          id: 11,
          src: require("../assets/images/img11.jpg")
        },
        {
          id: 12,
          src: require("../assets/images/img12.jpg")
        },
        {
          id: 13,
          src: require("../assets/images/img13.jpg")
        },
        {
          id: 15,
          src: require("../assets/images/img15.jpg")
        },
        {
          id: 16,
          src: require("../assets/images/img16.jpg")
        },
        {
          id: 17,
          src: require("../assets/images/img17.jpg")
        },
        {
          id: 18,
          src: require("../assets/images/img18.jpg")
        },
        {
          id: 19,
          src: require("../assets/images/img19.jpg")
        },
        {
          id: 20,
          src: require("../assets/images/img20.jpg")
        },
        {
          id: 21,
          src: require("../assets/images/img21.jpg")
        },
        {
          id: 22,
          src: require("../assets/images/img22.jpg")
        },
        {
          id: 23,
          src: require("../assets/images/img23.jpg")
        },
        {
          id: 24,
          src: require("../assets/images/img24.jpg")
        },
        {
          id: 25,
          src: require("../assets/images/img25.jpg")
        },
        {
          id: 26,
          src: require("../assets/images/img26.jpg")
        },
        {
          id: 27,
          src: require("../assets/images/img27.jpg")
        },
        {
          id: 28,
          src: require("../assets/images/img28.jpg")
        },
        {
          id: 29,
          src: require("../assets/images/img29.jpg")
        },
        {
          id: 30,
          src: require("../assets/images/img30.jpg")
        },
        {
          id: 31,
          src: require("../assets/images/img31.jpg")
        },
        {
          id: 32,
          src: require("../assets/images/img32.jpg")
        },
        {
          id: 33,
          src: require("../assets/images/img33.jpg")
        },
        {
          id: 34,
          src: require("../assets/images/img34.jpg")
        },
        {
          id: 35,
          src: require("../assets/images/img35.jpg")
        },
        {
          id: 36,
          src: require("../assets/images/img36.jpg")
        },
        {
          id: 37,
          src: require("../assets/images/img37.jpg")
        },
        {
          id: 38,
          src: require("../assets/images/img38.jpg")
        },
        {
          id: 39,
          src: require("../assets/images/img39.jpg")
        },
        {
          id: 40,
          src: require("../assets/images/img40.jpg")
        },
        {
          id: 41,
          src: require("../assets/images/img41.jpg")
        },
        {
          id: 42,
          src: require("../assets/images/img42.jpg")
        },
        {
          id: 43,
          src: require("../assets/images/img43.jpg")
        },
        {
          id: 44,
          src: require("../assets/images/img44.jpg")
        },
        {
          id: 45,
          src: require("../assets/images/img45.jpg")
        },
        {
          id: 46,
          src: require("../assets/images/img46.jpg")
        },
        {
          id: 47,
          src: require("../assets/images/img47.jpg")
        },
        {
          id: 48,
          src: require("../assets/images/img48.jpg")
        },
        {
          id: 49,
          src: require("../assets/images/img49.jpg")
        }



      ]
    };
  }
};
</script>