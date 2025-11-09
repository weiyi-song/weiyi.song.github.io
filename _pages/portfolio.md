---
layout: page
title: Portfolio
permalink: /portfolio/
description: 
nav: true
nav_order: 3
---

<!-- Portfolio: Performance Videos -->


<style>
  .video-portfolio {
    max-width: 1200px;
    margin: 0 auto;
  }
  
  .video-portfolio .col {
    margin-bottom: 2rem;
  }
  
  .video-portfolio .card {
    background: var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.3s, box-shadow 0.3s;
  }
  
  .video-portfolio .card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 24px rgba(0,0,0,0.15);
  }
  
  .video-portfolio .video-wrapper {
    position: relative;
    padding-bottom: 56.25%; /* 16:9 aspect ratio */
    height: 0;
    overflow: hidden;
    background: #000;
  }
  
  .video-portfolio .video-wrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
  }
  
  .video-portfolio .card-body {
    padding: 1.25rem;
  }
  
  .video-portfolio .video-title {
    font-size: 1.1rem;
    font-weight: 600;
    color: var(--global-theme-color);
    margin-bottom: 0.5rem;
  }
  
  .video-portfolio .video-description {
    font-size: 0.95rem;
    color: var(--global-text-color);
    opacity: 0.85;
    margin-bottom: 0;
  }
  
  .video-portfolio .video-meta {
    font-size: 0.85rem;
    color: var(--global-text-color);
    opacity: 0.6;
    margin-top: 0.5rem;
  }

  @media (max-width: 768px) {
    .video-portfolio .card-body {
      padding: 1rem;
    }
    
    .video-portfolio .video-title {
      font-size: 1rem;
    }
  }
</style>

<div class="video-portfolio">
  <div class="row row-cols-1 row-cols-md-2 g-4">
    
    <!-- Video 1 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/h7CCMny7rqI" 
            title="Performance 1"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
    
    <!-- Video 2 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/aBZVmhbrerA" 
            title="Performance 2"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
    
    <!-- Video 3 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/i0bu6Eizo8U" 
            title="Performance 3"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
    
    <!-- Video 4 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/LFsM_BEH2kI" 
            title="Performance 4"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
    
    <!-- Video 5 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/bAPj1S69O2c"
            title="Performance 5"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
    
    <!-- Video 6 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/IfHzkWCyGKA" 
            title="Performance 6"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
    
  </div>
  
  <!-- Row 4 -->
  <div class="row row-cols-1 row-cols-md-2 g-4 mt-0">
    
    <!-- Video 7 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/J_g5P9xa074"
            title="Performance 7"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
    
    <!-- Video 8 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/e34zCtESn_o" 
            title="Performance 8"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
      </div>
    </div>
    
  </div>
</div>


