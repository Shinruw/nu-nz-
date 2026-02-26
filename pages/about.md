---
layout: default
title: 關於暖字
description: 認識李淑貞老師與暖字表達寫作班的教學理念
permalink: /about/
---

<div class="page-hero">
  <div class="container">
    <h1>關於暖字</h1>
    <p>認識這個讓孩子對寫作產生安全感的地方</p>
  </div>
</div>

<section class="section">
  <div class="container">
    <div class="about-intro">
      <div class="about-photo">
        <div class="about-photo-placeholder">
          <svg width="56" height="56" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" style="opacity:0.4;">
            <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/>
            <circle cx="12" cy="7" r="4"/>
          </svg>
          <span>老師照片</span>
          <small>assets/images/teacher.jpg</small>
        </div>
      </div>
      <div class="about-text">
        <h2>李淑貞老師的故事</h2>
        <p>
          小時候，我是一個很不會表達自己的孩子。不是因為沒有感受，而是不知道怎麼把心裡的東西說出來、寫出來。直到有一天，有個老師讀了我的作文，然後跟我說：「你寫的這一段，讓我想起了我自己的阿嬤。」
        </p>
        <p>
          那一刻，我才發現——原來我寫的東西，真的可以觸動另一個人。那種感覺，改變了我和寫作的關係。
        </p>
        <p>
          後來我成為老師，我想把這種感覺給每一個孩子。不是要他們寫得「好」，而是要讓他們知道：自己的故事，值得被聽見。
        </p>
        <p style="font-style:italic;color:var(--brown-light);">
          — 李淑貞老師
        </p>
      </div>
    </div>
  </div>
</section>

<section class="section section--alt">
  <div class="container">
    <div class="section-header">
      <h2>教學理念</h2>
      <p>先暖心，再暖字</p>
      <div class="underline"></div>
    </div>
    <div class="values-grid" style="max-width:900px;margin:0 auto;">
      <div class="value-card">
        <div class="value-icon">❤️</div>
        <h3>溫暖</h3>
        <p>讓孩子對寫作產生安全感，先暖心，再暖字。在一個溫暖的環境裡，孩子才能放心打開心房。</p>
      </div>
      <div class="value-card">
        <div class="value-icon">🗣️</div>
        <h3>真誠對話</h3>
        <p>老師與孩子、老師與家長之間真實的雙向交流。每一篇作品都值得被認真閱讀與回應。</p>
      </div>
      <div class="value-card">
        <div class="value-icon">🌟</div>
        <h3>重視個體</h3>
        <p>每個孩子都有獨特的聲音，寫作是自我表達的出口。我們不追求統一的標準答案。</p>
      </div>
      <div class="value-card">
        <div class="value-icon">🌿</div>
        <h3>陪伴成長</h3>
        <p>不只是課程，更是一段共同走過的寫作旅程。老師在每個孩子身邊，一步一步陪著走。</p>
      </div>
    </div>
  </div>
</section>

<section class="section">
  <div class="container">
    <div class="section-header">
      <h2>寫作金三角</h2>
      <p>暖字的核心教學方法</p>
      <div class="underline"></div>
    </div>
    <div class="triangle-visual">
      <div class="triangle-top">
        <div class="triangle-label">畫面</div>
        <div class="triangle-desc">你看到了什麼？</div>
      </div>
      <div class="triangle-bottom">
        <div class="triangle-left">
          <div class="triangle-label">細節</div>
          <div class="triangle-desc">哪個細節讓你印象深刻？</div>
        </div>
        <div class="triangle-right">
          <div class="triangle-label">感受</div>
          <div class="triangle-desc">那時候你有什麼感覺？</div>
        </div>
      </div>
    </div>
    <div style="max-width:680px;margin:2.5rem auto 0;text-align:center;color:var(--brown-light);line-height:1.9;">
      <p>我不教孩子先想「要寫什麼主題」，而是先帶他們觀察——觀察一個畫面、一個細節、一種感受。當這三者都有了，文字自然就流出來了。</p>
    </div>
  </div>
</section>

<section class="section section--alt">
  <div class="container">
    <div class="section-header">
      <h2>課堂的樣子</h2>
      <p>真實的學習現場</p>
      <div class="underline"></div>
    </div>
    <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:1.5rem;max-width:900px;margin:0 auto;">
      {% for i in (1..3) %}
      <div style="background:var(--peach);border-radius:16px;height:220px;display:flex;flex-direction:column;align-items:center;justify-content:center;color:var(--brown-light);gap:0.5rem;font-size:0.88rem;">
        <svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1" style="opacity:0.4;">
          <rect x="3" y="3" width="18" height="18" rx="2"/>
          <circle cx="8.5" cy="8.5" r="1.5"/>
          <polyline points="21 15 16 10 5 21"/>
        </svg>
        <span>課堂照片 {{ i }}</span>
        <small>assets/images/class-{{ i }}.jpg</small>
      </div>
      {% endfor %}
    </div>
    <p style="text-align:center;color:var(--brown-light);font-size:0.88rem;margin-top:1rem;">請將課堂照片放置於 assets/images/ 目錄</p>
  </div>
</section>

<section class="section" style="text-align:center;">
  <div class="container">
    <h2 style="margin-bottom:1rem;">想讓孩子認識暖字？</h2>
    <p style="color:var(--brown-light);margin-bottom:2rem;">歡迎直接和老師聊聊</p>
    <a href="{{ '/contact' | relative_url }}" class="btn btn-orange">聯絡老師</a>
    &nbsp;&nbsp;
    <a href="{{ '/courses' | relative_url }}" class="btn" style="background:var(--peach);color:var(--brown);">查看課程</a>
  </div>
</section>
