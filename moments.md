---
layout: base
title: Moments
permalink: /moments/
---

<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
        margin: 0;
    }
    .gallery {
        display: grid;
        grid-template-columns: repeat(6, 1fr);
        gap: 18px;
        padding: 18px;
    }
    .photo {
        border: 0.5px solid #d3d3d3;
        padding: 5.5px;
        background: white;
        display: flex;
        flex-direction: column;
        align-items: center;
        overflow: hidden;
    }
    .photo img {
        width: 100%;
        height: auto;
        object-fit: cover;
    }
    .photo.tall {
        grid-column: span 2;
    }
    .photo.wide {
        grid-column: span 3;
    }
    .year-title {
        margin-top: 12px;
        font-size: 20px;
        padding-left: 20px;
        color:  #92b6f0;
    }
    .custom-quote {
      border-left: 2px solid rgba(52, 152, 219, 0);/* Change the color as desired */
      padding-left: 16px;/* Adjust the padding as needed */
      margin: 2;
      font-size: 16px; /* Example font size */
      color: #92b6f0;
    }
  </style>
</head>
<body>
<h2 class="year-title">2023</h2>
<div class="gallery">
    <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_1.jpg" alt="Tall Image">
    </div>
    <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_2.jpg" alt="Tall Image">
    </div>
        <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_3.jpg" alt="Tall Image">
    </div>
    <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_4.jpg" alt="Tall Image">
    </div>
    <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_5.jpg" alt="Tall Image">
    </div>
    <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_6.jpg" alt="Tall Image">
    </div>
    <div class="photo wide">
        <img src="{{ site.baseurl }}/assets/images/2023_7.jpg" alt="Wide Image">
    </div>
    <div class="photo wide">
        <img src="{{ site.baseurl }}/assets/images/2023_8.jpg" alt="Wide Image">
    </div>
    <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_9.jpg" alt="Tall Image">
    </div>
    <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_10.jpg" alt="Tall Image">
    </div>
    <div class="photo tall">
        <img src="{{ site.baseurl }}/assets/images/2023_11.jpg" alt="Tall Image">
    </div>
    <!-- Add more .photo divs with class 'wide' for wide images -->
</div>
</body>
</html>


