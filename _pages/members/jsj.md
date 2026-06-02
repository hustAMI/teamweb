---
layout: page
title: 
permalink: /people/jsj/
nav: false
---

<div class="member-detail">

  <div class="member-header">
    <div class="member-photo">
      <img src="{{ '/assets/img/members/jsj.jpg' | relative_url }}" alt="蒋叔稷">
    </div>

    <div class="member-info">
      <h1>蒋叔稷</h1>
      <p><strong>2025级硕士生</strong></p>
      <p>科技楼北315</p>
    </div>
  </div>

  <hr>

  <h2>个人简介</h2>

  <p>
  本人兴趣爱好：棒垒球🥎
  </p>

  <h2>研究方向</h2>

  <ul>
    <li>器件仿真</li>
    <li>MTJ热稳定性研究</li>
    
  </ul>

  

  <div class="back-button-wrap">
  <a class="member-back-button" href="{{ '/people/' | relative_url }}">← 返回</a>
</div>
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
