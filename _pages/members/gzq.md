---
layout: page
title: 
permalink: /people/gzq/
nav: false
---

<div class="member-detail">

  <div class="member-header">
    <div class="member-photo">
      <img src="{{ '/assets/img/members/gzq.jpg' | relative_url }}" alt="高卓祺">
    </div>

    <div class="member-info">
      <h1>高卓祺</h1>
      <p><strong>2025级硕士生</strong></p>
      <p>科技楼北315</p>
    </div>
  </div>

  <hr>

  <h2>个人简介</h2>

  <p>
  本人为集成电路学院硕士生，主要研究方向为磁定位系统与FPGA数字信号处理，关注磁场信号的采集、处理与定位算法实现。研究内容包括基于磁传感器的空间定位方法、FPGA实时数据处理架构以及相关硬件系统搭建。
  </p>

  <h2>研究方向</h2>

  <ul>
    <li>基于FPGA的磁定位系统开发</li>
    <li>数字电路设计、信号处理算法的硬件实现与优化。</li>
    
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
</style>
