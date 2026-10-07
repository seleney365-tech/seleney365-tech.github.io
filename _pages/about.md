---
layout: single
title: "About"
permalink: /
author_profile: true
---

<style>
  /* 卡片 */
  .card-block {
    background: #fafbfd;
    border: 1px solid #e1e4e8;
    border-radius: 10px;
    padding: 20px 24px;
    margin-bottom: 2em;
  }
  .card-block .block-title {
    color: #2a7ae2;
    font-size: 1.35em;
    font-weight: bold;
    margin-top: 0;
    margin-bottom: 1em;
    padding-bottom: 6px;
    border-bottom: 2px solid #2a7ae2;
  }
  .card-block ul {
    margin: 0;
    padding-left: 20px;
  }
  .card-block li {
    font-size: 0.95em;
    line-height: 1.7;
    color: #333;
    margin-bottom: 4px;
  }
  .card-block strong {
    color: #1a4f8a;
  }
  .card-block a {
    color: #2a7ae2;
    text-decoration: none;
  }
  .card-block a:hover {
    text-decoration: underline;
  }

  /* 导航按钮 */
  .nav-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
    gap: 12px;
  }
  .nav-button {
    display: block;
    background: #2a7ae2;
    color: #ffffff !important;
    padding: 12px 18px;
    border-radius: 8px;
    text-align: center;
    font-weight: bold;
    font-size: 0.95em;
    text-decoration: none !important;
    transition: background 0.2s;
  }
  .nav-button:hover {
    background: #1a4f8a;
  }

  /* 图片轮播 */
  .carousel-container {
    position: relative;
    max-width: 100%;
    margin: 0 auto;
    overflow: hidden;
    border-radius: 10px;
    background: #f0f0f0;
  }
  .carousel-slides {
    display: flex;
    transition: transform 0.4s ease;
  }
  .carousel-slide {
    min-width: 100%;
    box-sizing: border-box;
  }
  .carousel-slide img {
    width: 100%;
    display: block;
    border-radius: 10px;
  }
  .carousel-btn {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background: rgba(0, 0, 0, 0.45);
    color: #fff;
    border: none;
    font-size: 22px;
    padding: 8px 14px;
    cursor: pointer;
    border-radius: 50%;
    user-select: none;
  }
  .carousel-btn:hover {
    background: rgba(0, 0, 0, 0.7);
  }
  .carousel-btn.prev {
    left: 10px;
  }
  .carousel-btn.next {
    right: 10px;
  }
  .carousel-dots {
    text-align: center;
    margin-top: 10px;
  }
  .carousel-dots span {
    display: inline-block;
    width: 10px;
    height: 10px;
    margin: 0 5px;
    background: #c8d6e5;
    border-radius: 50%;
    cursor: pointer;
    transition: background 0.2s;
  }
  .carousel-dots span.active {
    background: #2a7ae2;
  }
</style>

<!-- 简介 -->
<div class="card-block" id="intro">
  <h2 class="block-title">👋 About Me</h2>
  <p>
    I am <strong>Siying (Selene) YANG</strong>, a Master's student in Economics at
    <strong>The Hong Kong University of Science and Technology (HKUST)</strong>.
    I received my Bachelor's degree in Economics (Economic Statistics) from
    <strong>Guangdong University of Foreign Studies</strong>.
  </p>
  <p>
    My interests lie in applying statistical and econometric methods to economic problems,
    with hands-on experience in financial modeling, investment research, and data analysis.
  </p>
</div>

<!-- 导航 -->
<div class="card-block" id="explore">
  <h2 class="block-title">🔎 Explore My Site</h2>
  <div class="nav-grid">
    <a class="nav-button" href="/career/">Career</a>
    <a class="nav-button" href="/publications/">Publications &amp; Competitions</a>
    <a class="nav-button" href="/academic/">Academic</a>
    <a class="nav-button" href="/skills/">Skills &amp; Activities</a>
    <a class="nav-button" href="/contact/">Contact</a>
  </div>
</div>

<!-- 图片轮播 -->
<div class="card-block" id="gallery">
  <h2 class="block-title">📸 Gallery</h2>
  <div class="carousel-container">
    <div class="carousel-slides" id="carouselSlides">
      <div class="carousel-slide"><img src="/images/gallery1.jpg" alt="Photo 1"></div>
      <div class="carousel-slide"><img src="/images/gallery2.jpg" alt="Photo 2"></div>
      <div class="carousel-slide"><img src="/images/gallery3.jpg" alt="Photo 3"></div>
    </div>
    <button class="carousel-btn prev" onclick="moveSlide(-1)">&#10094;</button>
    <button class="carousel-btn next" onclick="moveSlide(1)">&#10095;</button>
  </div>
  <div class="carousel-dots" id="carouselDots"></div>
</div>

<script>
  let currentSlide = 0;
  const slides = document.getElementById('carouselSlides');
  const totalSlides = slides.children.length;
  const dotsContainer = document.getElementById('carouselDots');

  // 生成小圆点
  for (let i = 0; i < totalSlides; i++) {
    const dot = document.createElement('span');
    if (i === 0) dot.classList.add('active');
    dot.onclick = () => goToSlide(i);
    dotsContainer.appendChild(dot);
  }

  function updateSlide() {
    slides.style.transform = `translateX(-${currentSlide * 100}%)`;
    const dots = dotsContainer.children;
    for (let i = 0; i < dots.length; i++) {
      dots[i].classList.toggle('active', i === currentSlide);
    }
  }

  function moveSlide(direction) {
    currentSlide = (currentSlide + direction + totalSlides) % totalSlides;
    updateSlide();
  }

  function goToSlide(index) {
    currentSlide = index;
    updateSlide();
  }

  // 自动播放（可选，每 5 秒切换一次，不想要就把这行删掉）
  setInterval(() => moveSlide(1), 5000);
</script>
