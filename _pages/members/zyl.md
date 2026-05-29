---
layout: page
title: 
permalink: /people/zyl/
nav: false
---

<div class="member-detail">

  <div class="member-header">
    <div class="member-photo">
      <img src="{{ '/assets/img/zyl.jpg' | relative_url }}" alt="朱玉良">
    </div>

    <div class="member-info">
      <h1>朱玉良</h1>
      <p><strong>博士生</strong></p>
      <p>科技楼北315</p>
    </div>
  </div>

  <hr>

  <h2>个人简介</h2>

  <p>
  这里填写朱玉良的个人简介。
  </p>

  <h2>研究方向</h2>

  <ul>
    <li>磁性存储器件</li>
    <li>自旋电子学</li>
    
  </ul>

  <h2>代表性成果</h2>

  <ul>
    <li>这里填写论文、专利或项目成果。</li>
  </ul>

  <p>
    <a href="{{ '/people/' | relative_url }}">← 返回科研团队</a>
  </p>

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
</style>
