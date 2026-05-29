---
layout: page
title: 
permalink: /people/yyh/
nav: false
---

<div class="member-detail">

  <div class="member-header">
    <div class="member-photo">
      <img src="{{ '/assets/img/members/yyh.jpg' | relative_url }}" alt="袁宇豪">
    </div>

    <div class="member-info">
      <h1>袁宇豪</h1>
      <p><strong>硕士生</strong></p>
      <p>科技楼北315</p>
    </div>
  </div>

  <hr>

  <h2>个人简介</h2>

  <p>
  本人为集成电路工程硕士，研究方向为FPGA设计与磁探测定位实现。主攻基于FPGA的磁定位系统开发，熟悉数字电路设计、信号处理算法的硬件实现与优化。
  </p>

  <h2>研究方向</h2>

  <ul>
    <li>基于FPGA的磁定位系统开发</li>
    <li>数字电路设计、信号处理算法的硬件实现与优化。</li>
    
  </ul>

  <h2>代表性成果</h2>

  <ul>
    <li>这里填写论文、专利或项目成果。</li>
  </ul>

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
