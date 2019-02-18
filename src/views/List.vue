<template>
  <div class="container">
    <div class="row">
      <Track v-for="(track, index) in tracks" :key="index" :track="track" />
    </div>
  </div>
</template>

<script>
import Track from "@/components/Track.vue";

export default {
  name: "list",
  components: {
    Track
  },

  data: function() {
    return {
      tracks: [
        {
          title: "The Best of Times",
          artist: "Dream Theater",
          album: "A Dramatic Turn of Events",
          art: require("@/assets/dt.jpg")
        },

        {
          title: "Hollow Years",
          artist: "Dream Theater",
          album: "Falling Into Infinity",
          art: require("@/assets/dt.jpg")
        },

        {
          title: "Basket Case",
          artist: "Green Day",
          album: "American Idiot",
          art: require("@/assets/dt.jpg")
        },

        {
          title: "Electric Sunrise",
          artist: "Plini",
          album: "Selenium Forest",
          art: require("@/assets/dt.jpg")
        },

        {
          title: "Miasma",
          artist: "Ghost",
          album: "Papa Emeritus II",
          art: require("@/assets/dt.jpg")
        }
      ]
    };
  }
};
</script>
