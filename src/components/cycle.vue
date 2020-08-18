<template>
  <v-carousel>
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    ></v-carousel-item>
  </v-carousel>
</template>

<script>
  export default {
    data () {
      return {
        items: [
          {
            src: 'https://cdn.pixabay.com/photo/2017/12/27/14/02/friends-3042751_1280.jpg',
          },
          {
            src: 'https://cdn.pixabay.com/photo/2014/11/28/08/40/paw-548634_1280.jpg',
          },
          {
            src: 'https://cdn.pixabay.com/photo/2018/07/28/00/10/autumn-3567035_1280.jpg',
          },
          {
            src: 'https://cdn.pixabay.com/photo/2015/07/27/19/11/black-and-white-863140_1280.jpg',
          },
        ],
      }
    },
  }
</script>
