<template>
  <div>
    <b-carousel
      id="carousel-1"
      v-model="slide"
      :interval="4000"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
      style="text-shadow: 1px 1px 2px #333"
      @sliding-start="onSlideStart"
      @sliding-end="onSlideEnd"
    >
      <!-- Text slides with image -->
      <b-carousel-slide
        img-src="https://www.kfc.co.th/Content/OnlineOrderingImages/Menu/Category/Carousel/wearyourway_TH.jpg"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://www.kfc.co.th/Content/OnlineOrderingImages/Menu/Category/Carousel/Tender_ALC_DLV_TH.jpg"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://www.kfc.co.th/Content/OnlineOrderingImages/Menu/Category/Carousel/ORTender_Party_Gang_TH.jpg"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://www.kfc.co.th/Content/OnlineOrderingImages/Menu/Category/Carousel/7FREE7_TH.jpg"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://www.kfc.co.th/Content/OnlineOrderingImages/Menu/Category/Carousel/BuddySnackBanner_TH.jpg"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://www.kfc.co.th/Content/OnlineOrderingImages/Menu/Category/Carousel/BigOrder_Banner_DLV_TH.jpg"
      ></b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  data() {
    return {
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    onSlideStart(slide) {
      this.sliding = true;
    },
    onSlideEnd(slide) {
      this.sliding = false;
    },
  },
};
</script>