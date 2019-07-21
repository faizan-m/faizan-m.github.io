---
layout: article
title: Quirks
key:    page-quirks
aside:
  toc: true
---

<style>
  .swiper-mime {
    height: 500px;
  }
  .swiper-mime .swiper__slide {
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
    color: #fff;
  }
  .swiper-mime .swiper__slide:nth-child(n) {
    background-color: #000;
  }
</style>

## Miming
I have been a member of the HYPE! mime troupe at Tufts where I was involved in acting, writing and directing skits. I love miming as a medium for story-telling because it demands that the plot be broken down into the most basic form of human expression; gestures and body language. And because of that it aspires to transcend beyond barriers of language and culture into something that is universally human. The time and experience within the troupe renewed my faith in our shared humanity that exists beyond social and geographic barriers.


<div class="swiper my-3 swiper-mime swiper-mime--0">
  <div class="swiper__wrapper">
    <div class="swiper__slide"><img class="lightbox-ignore" src="/assets/images/mime/1.jpg"/></div>
    <div class="swiper__slide"><img class="lightbox-ignore" src="/assets/images/mime/3.jpg"/></div>
    <div class="swiper__slide"><img class="lightbox-ignore" src="/assets/images/mime/4.jpg"/></div>
    <div class="swiper__slide"><img class="lightbox-ignore" src="/assets/images/mime/5.jpg"/></div>
    <div class="swiper__slide"><img class="lightbox-ignore" src="/assets/images/mime/6.jpg"/></div>
    <div class="swiper__slide"><img class="lightbox-ignore" src="/assets/images/mime/7.jpg"/></div>
    <div class="swiper__slide"><img class="lightbox-ignore" src="/assets/images/mime/8.jpg"/></div>
  </div>
  <!-- <div class="swiper__pagination"></div> -->
  <div class="swiper__button swiper__button--prev fas fa-chevron-left"></div>
  <div class="swiper__button swiper__button--next fas fa-chevron-right"></div>
  <!-- <div class="swiper-scrollbar"></div> -->
</div>

## Fencing

<div class="grid-container">
  <div class="grid grid--p-3">

  <div class="cell cell--shrink">
  <img class="image image--xl" src="/assets/images/fencing/1.jpg"/>
  </div>

  <div class="cell cell--auto">
  I started fencing sophomore year of college without any prior experience. Fencing is fascinating to me for its fast-paced strategy and reliance on quick reflexes. Though I am still very much a new-comer to this sport, I have had the opportunity to participate in some tournaments on behalf of the Tufts Fencing Foil Squad.
  </div>

  </div>
</div>

## International Mathematical Olympiad 2016
<div class="hero hero--dark" style='height: 500px; background-image: url("/assets/images/imo.jpg");'>
</div>

During highschool I was heavily involved in math competitions, this culminated in me getting selected for the national Pakistani team for IMO 2016. The selection and training was an intense, gruelling process but I learned so much about mathematical problem solving and analysis through it. The camps and the competition are also a source of some of my long standing friendships.

## Books, Movies and Art
I am a big fan of the written works of Bulleh Shah, Douglas Adams and Terry Pratchet. I greatly appreciate their unique and whimsical approach to life and humanity. I also find it pretty amazing that there is way more in common between Bulleh (a devout Sufi) and Douglas (an equally devout atheist) than one would expect.

My favorite movie is Cloud Atlas. If there is a reasonable answer to the meaning of life, the universe and everything then it is definitely in there somewhere.

I recently learned about [Electric Sheep](https://electricsheep.org/) and it is one of the coolest things I have ever seen. It is crowd-sourced art powered by genetic algorithms that iteratively evolves based on feedback from the users. It never fails to mesmerize me every time I watch one of its clips.

<script>
  {%- include scripts/lib/swiper.js -%}
  var SOURCES = window.TEXT_VARIABLES.sources;
  window.Lazyload.js(SOURCES.jquery, function() {
    $('.swiper-mime--0').swiper();
  });
</script>