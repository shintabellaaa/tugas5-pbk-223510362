<template>
    <b-carousel
      id="carousel-1"
      style="text-shadow: 1px 1px 2px #333;"
      controls
      indicators
      background="#ababab"
      img-width="1024"
      img-height="480"
    >
      <b-carousel-slide
        caption="First Slide"
        text="Nulla vitae elit libero, a pharetra augue mollis interdum."
      ></b-carousel-slide>
      <b-carousel-slide
        caption="Second Slide"
        text="Lorem ipsum dolor sit amet, consectetur adipiscing elit."
      ></b-carousel-slide>
      <b-carousel-slide
        caption="Third Slide"
        text="Praesent commodo cursus magna, vel scelerisque nisl consectetur."
      ></b-carousel-slide>
    </b-carousel>
  </template>
  
  <script>
  export default {
    name: 'Carousel'
  }
  </script>
  