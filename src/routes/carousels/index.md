---
layout: carouselLayout
---

<script>
  import { Carousel } from '$lib/index';
  import { images } from './imageData';
  let showThumbs=false
  let showIndicators=false
  let showCaptions=false
  let slideControls=false
</script>

<h1 class="text-3xl w-full dark:text-white pb-8">Carousel</h1>

<div class="container justify-center rounded-xl mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <div class="max-w-4xl">
    <Carousel {images} />
  </div>
</div>

```html
<script>
  import { Carousel } from '$lib/index';
  const images = [
  {
    id: 0,
    name: "Cosmic timetraveler",
    imgurl: "/images/carousel/cosmic-timetraveler-pYyOZ8q7AII-unsplash.webp",
    attribution: "cosmic-timetraveler-pYyOZ8q7AII-unsplash.com",
  },
  {
    id: 1,
    name: "Cristina Gottardi",
    imgurl: "/images/carousel/cristina-gottardi-CSpjU6hYo_0-unsplash.webp",
    attribution: "cristina-gottardi-CSpjU6hYo_0-unsplash.com",
  },
  {
    id: 2,
    name: "Johannes Plenio",
    imgurl: "/images/carousel/johannes-plenio-RwHv7LgeC7s-unsplash.webp",
    attribution: "johannes-plenio-RwHv7LgeC7s-unsplash.com",
  },
  {
    id: 3,
    name: "Jonatan Pie",
    imgurl: "/images/carousel/jonatan-pie-3l3RwQdHRHg-unsplash.webp",
    attribution: "jonatan-pie-3l3RwQdHRHg-unsplash.com",
  },
  {
    id: 4,
    name: "Mark Harpur",
    imgurl: "/images/carousel/mark-harpur-K2s_YE031CA-unsplash.webp",
    attribution: "mark-harpur-K2s_YE031CA-unsplash",
  },
  {
    id: 5,
    name: "Pietro De Grandi",
    imgurl: "/images/carousel/pietro-de-grandi-T7K4aEPoGGk-unsplash.webp",
    attribution: "pietro-de-grandi-T7K4aEPoGGk-unsplash",
  },
  {
    id: 6,
    name: "Sergey Pesterev",
    imgurl: "/images/carousel/sergey-pesterev-tMvuB9se2uQ-unsplash.webp",
    attribution: "sergey-pesterev-tMvuB9se2uQ-unsplash",
  },
  {
    id: 7,
    name: "Solo travel goals",
    imgurl: "/images/carousel/solotravelgoals-7kLufxYoqWk-unsplash.webp",
    attribution: "solotravelgoals-7kLufxYoqWk-unsplash",
  },
];
</script>

<Carousel {images} />
```

<h2 class="text-2xl w-full dark:text-white py-8">Without thumbnails</h2>

<p class="dark:text-white text-lg">The `showThumbs` is set to `true`. Set it to `false` to hide it.</p>

<div class="container justify-center rounded-xl mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <div class="max-w-4xl">
    <Carousel {images} {showThumbs}/>
  </div>
</div>

```html
<script>
    let showThumbs=false
</script>

<Carousel {images} {showThumbs}/>
```

<h2 class="text-2xl w-full dark:text-white py-8">Without caption</h2>

<p class="dark:text-white text-lg">To hide the caption, set `showCaptions` to `false`.</p>

<div class="container justify-center rounded-xl mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <div class="max-w-4xl">
    <Carousel {images} {showThumbs} {showCaptions}/>
  </div>
</div>

```html
<script>
  let showThumbs=false
  let showCaptions=false
</script>

<Carousel {images} {showThumbs} {showCaptions}/>
```

<h2 class="text-2xl w-full dark:text-white py-8">Without indicators</h2>

<p class="dark:text-white text-lg">To hide the indicators, set `showIndicators` to `false`.</p>

<div class="container justify-center rounded-xl mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <div class="max-w-4xl">
    <Carousel {images} {showThumbs} {showCaptions} {showIndicators}/>
  </div>
</div>

```html
<script>
  let showThumbs=false
  let showCaptions=false
  let showIndicators=false
</script>

<Carousel {images} {showThumbs} {showCaptions} {showIndicators}/>
```

<h2 class="text-2xl w-full dark:text-white py-8">Without Slide controlers</h2>

<p class="dark:text-white text-lg">To hide the slide controlers, set `slideControls` to `false`.</p>

<div class="container justify-center rounded-xl mx-auto bg-gradient-to-r bg-white dark:bg-gray-900 border border-gray-200 dark:border-gray-700 p-2 sm:p-6">
  <div class="max-w-4xl">
    <Carousel {images} {showThumbs} {showCaptions} {slideControls}/>
  </div>
</div>

```html
<script>
  let showThumbs=false
  let showCaptions=false
  let slideControls=false
</script>

<Carousel {images} {showThumbs} {showCaptions} {slideControls}/>
```