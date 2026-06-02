---
layout: page
title: 
permalink: /people/wdh/
nav: false
---

<div class="member-detail">

  <div class="member-header">
    <div class="member-photo">
      <img src="{{ '/assets/img/members/wdh.jpg' | relative_url }}" alt="吴帝桦">
    </div>

    <div class="member-info">
      <h1>吴帝桦</h1>
      <p><strong>2025级直博生</strong></p>
      <p>科技楼北315</p>
    </div>
  </div>

  <hr>

  <h2>个人简介</h2>

  <p>
  主要从事自旋电子学与磁性存储器相关研究，关注自旋轨道矩驱动的磁化翻转以及磁畴、斯格明子的高速动力学过程，对非晶亚铁磁体系中非均匀性问题尤其感兴趣。平时既做器件实验，也喜欢折腾高速测试与测量系统，希望把复杂的磁动力学现象测得更清楚一些。科研之外，喜欢记录自然与人文风景，也在学习乐器和坚持运动。
  </p>

  <h2>研究方向</h2>

  <ul>
    <li>自旋轨道矩驱动的磁化翻转</li>
    <li>磁畴、斯格明子的高速动力学过程</li>
    <li>非晶亚铁磁体系中非均匀性问题</li>
    <li>高速测试与测量系统</li>
  
  </ul>

  <h2>代表性成果</h2>

  <ul>
    <li>这里填写论文、专利或项目成果。</li>
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
