<template>
  <div class="heroBlock">
    <v-carousel cycle hide-delimiters>
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
        reverse-transition="fade-transition"
        transition="fade-transition"
      >
        <v-row class="title fill-height hidden-xs-only" align="center" justify="center" >{{ item.title }}</v-row>
      </v-carousel-item>
    </v-carousel>
  </div>
</template>

<script>
export default {
  name: "Hero",
  data() {
    return {
      items: [
        {
          src: require("../assets/images/img-carousel1.jpeg"),
          title: "พวกเราทุกคนคือทีม"
        },
        {
          src: require("../assets/images/img-carousel2.jpg"),
          title: "เป็นน้ำหนึ่งใจเดียว"
        },
        {
          src: require("../assets/images/img-carousel3.jpg"),
          title: "คงอยู่นิจนิรันดร"
        },
        {
          src: require("../assets/images/img-carousel4.jpg"),
          title: "ไม่หวั่นอุปสรรค"
        }
      ]
    };
  }
};
</script>