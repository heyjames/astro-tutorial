---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'INSTactical'
pubDate: 2024-09-06
dates: 'Jan 2019 - Jan 2021'
description: ''
type: 'website'
image:
    url: '/../../src/instactical-01.jpg'
    alt: 'The full Astro logo.'
    width: '750'
tags: ["Website"]
---
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.css" />
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.8.1/slick.min.js"></script>

<script>
$(document).ready(function(){
    $('.carousel').slick({
        autoplay: true,
        autoplaySpeed: 3000,  // 3 seconds per slide
        arrows: true,         // Adds next/prev buttons
        dots: true,           // Adds navigation dots
        infinite: true,       // Loop the slides
        speed: 500            // Transition speed
    })
});
</script>
<div class="carousel">
  <div><img src="../../src/instactical-home.png" alt="Picture 1"></div>
  <div><img src="../../src/instactical-blog.png" alt="Picture 2"></div>
  <div><img src="../../src/instactical-blog-detail.png" alt="Picture 3"></div>

</div>
<style>
  .carousel img {
    width: 100%;
    height: auto;
  }
</style>
## Tools
- Node.js
- MongoDB
- Edge templating
- HTML
- Bulma CSS framework