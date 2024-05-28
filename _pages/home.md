---
title: "Resp Cell Atlas - Home"
layout: homelay
excerpt: "Resp Cell Atlas - Respiratory Data Centre: Facilitating Respiratory Disease Research with big data"
sitemap: true
permalink: /
---
<br/>
<br/>
<br/>
<div style="text-align:center;">
<!--h3 style="font-size:50px; font-weight:bold;">ATLAS</h3-->
</div>





<div class="container">
<div class="row" style="display: flex; justify-content: space-between;"> <!-- 两端对齐-->
<div class="col-lg-3 text-center custom-column">
<div class="img-circle card photo-card card-clickable" onclick="handleClick(this)">
<a href="#" onclick="showImage0('{{ site.url }}{{ site.baseurl }}/images/homePage/umapnose.png'); return false">
<img src="{{ site.url }}{{ site.baseurl }}/images/homePage/nose-pharynx.png" class="rounded-circle" />
</a>
</div>
<div>
<p class="text-center" style="margin-top: 16px;">
<b style="font-size: 24px;">
<a href="#" onclick="showImage0('{{ site.url }}{{ site.baseurl }}/images/homePage/umapnose.png'); return false">Nose and pharynx</a>
</b>
</p>
</div>
</div>


<div class="col-lg-3 text-center custom-column">
<div class="img-circle card photo-card card-clickable" onclick="handleClick(this)">
<a href="#" onclick="showImage0('{{ site.url }}{{ site.baseurl }}/images/homePage/umapairway.png'); return false">
<img src="{{ site.url }}{{ site.baseurl }}/images/homePage/airway.png" class="rounded-circle" />
</a>
</div>
<div>
<p class="text-center" style="margin-top: 16px;">
<b style="font-size: 24px;">
<a href="#" onclick="showImage0('{{ site.url }}{{ site.baseurl }}/images/homePage/umapairway.png'); return false">Airway</a>
</b>
</p>
</div>
</div>


<div class="col-lg-3 text-center custom-column">
<div class="img-circle card photo-card card-clickable" onclick="handleClick(this)">
<a href="#" onclick="showImage0('{{ site.url }}{{ site.baseurl }}/images/homePage/umaplung.png'); return false">
<img src="{{ site.url }}{{ site.baseurl }}/images/homePage/lung1.png" class="rounded-circle" />
</a>
</div>
<div>
<p class="text-center" style="margin-top: 16px;">
<b style="font-size: 24px;">
<a href="#" onclick="showImage0('{{ site.url }}{{ site.baseurl }}/images/homePage/umaplung.png'); return false">Lung</a>
</b>
</p>
</div>
</div>
</div>
</div>





<br/><br/><br/>

<div class="container">
<div class="row" >
<div class="image-container">
<img id="photo" src="{{ site.url }}{{ site.baseurl }}/images/homePage/umapnose.png" alt="Default Photo" style="max-height: 450px;">
</div>
</div>
</div>

<!-- <h3>Cite us </h3>
<p>Chen, Xinyue & Huang, Yin & Huang, Ziliang & Xu, Lahong & Huang, Liangfeng & Ye, Mingli & You, Renke & Zhang, Xuegong & Miao, Zhichao*. (2023). Brain Cell Atlas: An Integrative Ensemble of Cell Transcriptomes Across Human Brain Regions. 10.21203/rs.3.rs-3221500/v1.</p>
<br/> -->

<h3>Cite us </h3>
<div class="left-aligned" style="width: 100%;">
Liangfeng Huang, Shuo Feng, Ziliang Huang, Yin Huang, Ke Fang, Ying Ao, Zhichao Miao <br>
<strong style="color:#587B39;font-weight: bold">Resp Cell Atlas: An atlas of respiratory system cells.</strong><br>
<a> Unpublished</a>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    var adultButton = document.querySelector('.col-lg-4:nth-child(1) .card-clickable');
    adultButton.click();
  });
  function showImage0(photoName) {
    var photoElement = document.getElementById('photo');
    photoElement.src = photoName;
    photoElement.alt = photoName;
  }
</script>

<style>
  .image-container {
    max-width: 100%;
    max-height: 100%;
    background-color: none;
    justify-content: center;
    align-items: center;
    box-shadow: none;
  }
  
  .image-container img {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
</style>
<style>
    .photo-card {
/*         width: 350px;
        height: 350px; */
        border: 10px solid #ccc; 
        overflow: hidden;
        border-radius: 50%;
        position: relative;
        background-size: cover;
 /*        display: flex;  
        justify-content: right; /* 水平居中对齐 */
        /* align-items: right;  */
    }
    .photo-card:hover img {
        transform: scale(1.1);
    }
    .photo-card img {
        display: block;
        width: 100%;
        height: 100%;
        object-fit: cover;
        transition: transform 0.3s;
    }
    .photo-card.clicked {
        border-color: #587B39;
    }
</style>
<script>
  var clickedCard = null;

  function handleClick(card) {
    if (clickedCard !== null) {
      clickedCard.classList.remove("clicked");
    }

    card.classList.add("clicked");
    clickedCard = card;
  }
</script>

<style>
    .custom-column {
        margin: 0 55px; /* 设置列之间的间距 */
    }
</style>