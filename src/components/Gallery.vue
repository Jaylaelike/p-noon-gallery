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
        },

        {
          id: 50,
          src: require("../assets/images/img50.jpg")
        },
        {
          id: 51,
          src: require("../assets/images/img51.jpg")
        },
        {
          id: 52,
          src: require("../assets/images/img52.jpg")
        },
        {
          id: 53,
          src: require("../assets/images/img53.jpg")
        },
        {
          id: 54,
          src: require("../assets/images/img54.jpg")
        },
        {
          id: 55,
          src: require("../assets/images/img55.jpg")
        },
        {
          id: 56,
          src: require("../assets/images/img56.jpg")
        },
        {
          id: 57,
          src: require("../assets/images/img57.jpg")
        },
        {
          id: 58,
          src: require("../assets/images/img58.jpg")
        },
        {
          id: 59,
          src: require("../assets/images/img59.jpg")
        },

        {
          id: 60,
          src: require("../assets/images/img60.jpg")
        },
        {
          id: 61,
          src: require("../assets/images/img61.jpg")
        },
        {
          id: 62,
          src: require("../assets/images/img62.jpg")
        },
        {
          id: 63,
          src: require("../assets/images/img63.jpg")
        },
        {
          id: 64,
          src: require("../assets/images/img64.jpg")
        },
        {
          id: 65,
          src: require("../assets/images/img65.jpg")
        },
        {
          id: 66,
          src: require("../assets/images/img66.jpg")
        },
        {
          id: 67,
          src: require("../assets/images/img67.jpg")
        },
        {
          id: 68,
          src: require("../assets/images/img68.jpg")
        },
        {
          id: 69,
          src: require("../assets/images/img69.jpg")
        },

        {
          id: 70,
          src: require("../assets/images/img70.jpg")
        },
        {
          id: 71,
          src: require("../assets/images/img71.jpg")
        },
        {
          id: 72,
          src: require("../assets/images/img72.jpg")
        },
        {
          id: 73,
          src: require("../assets/images/img73.jpg")
        },
        {
          id: 74,
          src: require("../assets/images/img74.jpg")
        },
        {
          id: 75,
          src: require("../assets/images/img75.jpg")
        },
        {
          id: 76,
          src: require("../assets/images/img76.jpg")
        },
        {
          id: 77,
          src: require("../assets/images/img77.jpg")
        },
        {
          id: 78,
          src: require("../assets/images/img78.jpg")
        },
        {
          id: 79,
          src: require("../assets/images/img79.jpg")
        },

        {
          id: 80,
          src: require("../assets/images/img80.jpg")
        },
        {
          id: 81,
          src: require("../assets/images/img81.jpg")
        },
        {
          id: 82,
          src: require("../assets/images/img82.jpg")
        },
        {
          id: 83,
          src: require("../assets/images/img83.jpg")
        },
        {
          id: 84,
          src: require("../assets/images/img84.jpg")
        },
        {
          id: 85,
          src: require("../assets/images/img85.jpg")
        },
        {
          id: 86,
          src: require("../assets/images/img86.jpg")
        },
        {
          id: 87,
          src: require("../assets/images/img87.jpg")
        },
        {
          id: 88,
          src: require("../assets/images/img88.jpg")
        },
        {
          id: 89,
          src: require("../assets/images/img89.jpg")
        },

        {
          id: 90,
          src: require("../assets/images/img90.jpg")
        },
        {
          id: 91,
          src: require("../assets/images/img91.jpg")
        },
        {
          id: 92,
          src: require("../assets/images/img92.jpg")
        },
        {
          id: 93,
          src: require("../assets/images/img93.jpg")
        },
        {
          id: 94,
          src: require("../assets/images/img94.jpg")
        },
        {
          id: 95,
          src: require("../assets/images/img95.jpg")
        },
        {
          id: 96,
          src: require("../assets/images/img96.jpg")
        },
        {
          id: 97,
          src: require("../assets/images/img97.jpg")
        },
        {
          id: 98,
          src: require("../assets/images/img98.jpg")
        }


      ]
    };
  }
};
</script>