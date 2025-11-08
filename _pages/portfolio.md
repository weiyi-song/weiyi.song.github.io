---
layout: page
title: Portfolio
permalink: /portfolio/
description: Performance videos and highlights
nav: true
nav_order: 3
---

<!-- Portfolio: Performance Videos -->
## 🎭 Performance Portfolio

<style>
  .video-portfolio {
    max-width: 1200px;
    margin: 0 auto;
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
        <div class="card-body">
          <h3 class="video-title">Performance Title 1</h3>
          <p class="video-description">
            Description of your performance, the role you played, the venue, or any other details you'd like to share.
          </p>
          <p class="video-meta">Date or Venue</p>
        </div>
      </div>
    </div>
    
    <!-- Video 2 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID_2" 
            title="Performance 2"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
        <div class="card-body">
          <h3 class="video-title">Performance Title 2</h3>
          <p class="video-description">
            Description of your performance, the role you played, the venue, or any other details you'd like to share.
          </p>
          <p class="video-meta">Date or Venue</p>
        </div>
      </div>
    </div>
    
    <!-- Video 3 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID_3" 
            title="Performance 3"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
        <div class="card-body">
          <h3 class="video-title">Performance Title 3</h3>
          <p class="video-description">
            Description of your performance, the role you played, the venue, or any other details you'd like to share.
          </p>
          <p class="video-meta">Date or Venue</p>
        </div>
      </div>
    </div>
    
    <!-- Video 4 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID_4" 
            title="Performance 4"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
        <div class="card-body">
          <h3 class="video-title">Performance Title 4</h3>
          <p class="video-description">
            Description of your performance, the role you played, the venue, or any other details you'd like to share.
          </p>
          <p class="video-meta">Date or Venue</p>
        </div>
      </div>
    </div>
    
    <!-- Video 5 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID_5" 
            title="Performance 5"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
        <div class="card-body">
          <h3 class="video-title">Performance Title 5</h3>
          <p class="video-description">
            Description of your performance, the role you played, the venue, or any other details you'd like to share.
          </p>
          <p class="video-meta">Date or Venue</p>
        </div>
      </div>
    </div>
    
    <!-- Video 6 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID_6" 
            title="Performance 6"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
        <div class="card-body">
          <h3 class="video-title">Performance Title 6</h3>
          <p class="video-description">
            Description of your performance, the role you played, the venue, or any other details you'd like to share.
          </p>
          <p class="video-meta">Date or Venue</p>
        </div>
      </div>
    </div>
    
    <!-- Video 7 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID_7" 
            title="Performance 7"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
        <div class="card-body">
          <h3 class="video-title">Performance Title 7</h3>
          <p class="video-description">
            Description of your performance, the role you played, the venue, or any other details you'd like to share.
          </p>
          <p class="video-meta">Date or Venue</p>
        </div>
      </div>
    </div>
    
    <!-- Video 8 -->
    <div class="col">
      <div class="card h-100">
        <div class="video-wrapper">
          <iframe 
            src="https://www.youtube.com/embed/YOUR_VIDEO_ID_8" 
            title="Performance 8"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
            allowfullscreen>
          </iframe>
        </div>
        <div class="card-body">
          <h3 class="video-title">Performance Title 8</h3>
          <p class="video-description">
            Description of your performance, the role you played, the venue, or any other details you'd like to share.
          </p>
          <p class="video-meta">Date or Venue</p>
        </div>
      </div>
    </div>
    
  </div>
</div>

---

**How to add your YouTube videos:**

1. Go to your YouTube video
2. Click "Share" → "Embed"
3. Copy the video ID from the URL (the part after `https://www.youtube.com/watch?v=`)
4. Replace `YOUR_VIDEO_ID_1`, `YOUR_VIDEO_ID_2`, etc. with your actual video IDs
5. Update the titles, descriptions, and dates for each video

**Example:** If your video URL is `https://www.youtube.com/watch?v=dQw4w9WgXcQ`, your video ID is `dQw4w9WgXcQ`
