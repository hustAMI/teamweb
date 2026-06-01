---
layout: page
title: 
permalink: /people/ljx/
nav: false
---

<div class="member-detail">

  <div class="member-header">
    <div class="member-photo">
      <img src="{{ '/assets/img/members/ljx.jpg' | relative_url }}" alt="刘嘉新">
    </div>

    <div class="member-info">
      <h1>刘嘉新</h1>
      <p><strong>2026级直博生</strong></p>
      <p>科技楼北315</p>
    </div>
  </div>

  <hr>

  <h2>个人简介</h2>

  <p>
  本人刘嘉新，华中科技大学物理学院2026级直博生，主要从事磁性存储器件与自旋电子学相关研究。研究兴趣包括自旋轨道矩驱动的磁化翻转、磁畴与畴壁动力学、磁性异质结构中的有效场调控，以及相关磁性器件的高速表征与应用探索。
  </p>

  <h2>研究方向</h2>

  <ul>
    <li>磁性存储器件</li>
    <li>自旋电子学</li>
    <li>磁畴动力学与时间分辨磁光表征</li>
    
  </ul>

  <h2>代表性成果</h2>

  <div class="publications">
    {% bibliography -f papers -q @*[ljx=true] %}
  </div>

  <p>
    <a href="{{ '/people/' | relative_url }}">← 返回</a>
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
