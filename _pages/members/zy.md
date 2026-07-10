---
layout: page
title: 
permalink: /people/zy/
nav: false
---

<div class="member-detail">

  <div class="member-header">
    <div class="member-photo">
      <img src="{{ '/assets/img/members/zy.jpg' | relative_url }}" alt="张杨">
    </div>

    <div class="member-info">
      <h1>张杨</h1>
      <p><strong>2026级直博生</strong></p>
      <p>科技楼北315</p>
    </div>
  </div>

  <hr>

  <h2>个人简介</h2>

  <p>
  本人研究方向：磁性存储器件、自旋电子学
  </p>

  <h2>研究方向</h2>

  <ul>
    <li>磁性存储器件</li>
    <li>自旋电子学</li>
    
  </ul>

 

<div class="back-button-wrap">
  <a class="member-back-button" href="{{ '/people/' | relative_url }}">← 返回</a>
</div>
</div>

<style>
.member-detail {
  margin-top: 1rem;
}

.member-header {
  display: flex;
  align-items: flex-start;
  gap: 2rem;
  margin-bottom: 1.5rem;
}

.member-photo img {
  width: 180px;
  max-width: 100%;
  border-radius: 0.25rem;
  box-shadow: 0 3px 8px rgba(0, 0, 0, 0.12);
}

.member-info h1 {
  margin-top: 0;
  margin-bottom: 0.8rem;
}

@media (max-width: 600px) {
  .member-header {
    flex-direction: column;
  }
}

  /* 代表性成果标题和下面灰线距离更近 */
.member-detail .representative-title {
  margin-bottom: 0.2rem;
}

.member-detail .representative-publications {
  margin-top: 0 !important;
}

/* 控制 jekyll-scholar 自动生成的年份横线位置 */
.member-detail .representative-publications h2.bibliography {
  margin-top: 0.3rem !important;
  padding-top: 0.7rem !important;
}

/* 返回按钮整体位置：往下放 */
.back-button-wrap {
  margin-top: 3rem;
  margin-bottom: 2rem;
}

/* 返回按钮样式 */
.member-back-button {
  display: inline-block;
  padding: 0.45rem 0.9rem;
  border: 1px solid #007bff;
  border-radius: 0.35rem;
  color: #007bff;
  text-decoration: none;
  font-weight: 500;
  line-height: 1.2;
}

/* 鼠标放上去时的效果 */
.member-back-button:hover {
  background-color: #007bff;
  color: #ffffff;
  text-decoration: none;
}
</style>
