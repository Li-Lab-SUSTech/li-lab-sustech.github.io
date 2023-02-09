---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<style>
    .area_pics img{
        width:380px;
        margin-left:50px
        float:left;
    }
  
        .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
        overflow: hidden;
      }
      
      .mySlides {
        display: none;
      }
      
      .prev, .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        margin-top: -22px;
        padding: 16px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
      }
      
      .next {
        right: 0;
        border-radius: 3px 0 0 3px;
      }
      
      .prev:hover, .next:hover {
        background-color: rgba(0,0,0,0.8);
      }
  
      .news {
      width:800px;
      height: 150px;
      overflow-y: auto;
    }
</style>
<body align="justify">
<div class="area_pics">
 <img src="/images/research1.png" />
 <img src="/images/research2.png" />
</div>
<div class="area_pics">
 <img src="/images/research3.png" />
 <img src="/images/research4.jpg" />
</div>
  <br>
<div>
   <h1> News about the laboratory</h1>
   <hr/> 
<div class="news">

<li>Welcome our new research assistant Zeyu Xi! -- 2022.06.13</li>
<li>Welcome our new research assistant Jingwen Zhang!--2022.06.08</li>
<li>DMO PSF paper is out at Optics Letters! Congratulations Shuang Fu!--2022.06.08</li>
<li> globLoc paper is out at Nature Communications! Congratulations Wei Shi!--2022.06.06</li>
<li>Welcome our new research assistant Zeyu Xi! -- 2022.06.13</li>
<li>Welcome our new research assistant Jingwen Zhang!--2022.06.08</li>
<li>DMO PSF paper is out at Optics Letters! Congratulations Shuang Fu!--2022.06.08</li>
<li> globLoc paper is out at Nature Communications! Congratulations Wei Shi!--2022.06.06</li>
  </div>
   </div>   
<br>
<h1>What we do </h1>
   <hr/> 
  <p><b>Seeing is believing! </b>We firmly believe that resolution determines the depth of the research. We are interested to use super-resolution microscopy to show the wonders of the microscopic world. To achieve this, we collaborate heavily with biologists and develop a range of interdisciplinary technologies including new optics theories, advanced algorithms, smart hardware design and imaging strategies for better resolution, deeper depth, and faster speed. We embrace the open science and hope that our work will promote both the advancement of science and technology.</p>

<h1>What we are </h1>
     <hr/> 
  <div class="slideshow-container">
      <div class="mySlides"> 
        <img src="/images/team1.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team2.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team3.png" style="width:100%">
      </div>
          <div class="mySlides"> 
        <img src="/images/team4.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team5.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team6.png" style="width:100%">
      </div>
          <div class="mySlides"> 
        <img src="/images/team7.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team8.png" style="width:100%">
      </div>
              <div class="mySlides"> 
        <img src="/images/team9.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team10.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team11.png" style="width:100%">
      </div>
          <div class="mySlides"> 
        <img src="/images/team12.png" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/team13.png" style="width:100%">
      </div>
      <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
      <a class="next" onclick="plusSlides(1)">&#10095;</a>
    </div>
  <p>Our group is a mix of physicist, engineer, computer scientist, biologist and chemist.</p>
    <script>
      var slideIndex = 5;
      showSlides(slideIndex);
      
      function plusSlides(n) {
        showSlides(slideIndex += n);
      }
      
      function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        if (n > slides.length) {slideIndex = 1}
        if (n < 1) {slideIndex = slides.length}
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        slides[slideIndex-1].style.display = "block";
      }
    </script>
 
</body>





