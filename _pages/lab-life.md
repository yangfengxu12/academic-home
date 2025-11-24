---
layout: archive
title: "Lab Life"
permalink: /lab-life/
author_profile: true
---

{% include base_path %}

## Lab Activities & Memories

<div class="gallery">
  <div class="gallery-item">
    <img src="{{ base_path }}/images/lab-life/photo1.jpg" alt="Lab photo 1">
    <p class="caption">Caption for photo 1</p>
  </div>
  
  <div class="gallery-item">
    <img src="{{ base_path }}/images/lab-life/photo2.jpg" alt="Lab photo 2">
    <p class="caption">Caption for photo 2</p>
  </div>
  
  <div class="gallery-item">
    <img src="{{ base_path }}/images/lab-life/photo3.jpg" alt="Lab photo 3">
    <p class="caption">Caption for photo 3</p>
  </div>
</div>

<style>
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 20px;
    margin-top: 20px;
  }
  
  .gallery-item {
    text-align: center;
  }
  
  .gallery-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
  }
  
  .gallery-item img:hover {
    transform: scale(1.05);
  }
  
  .gallery-item .caption {
    margin-top: 10px;
    font-size: 0.9em;
    color: #666;
  }
</style>
