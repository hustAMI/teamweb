---
layout: page
title: 
permalink: /people/lcy/
nav: false
---

<div class="member-detail">

  <div class="member-header">
    <div class="member-photo">
      <img src="{{ '/assets/img/members/lcy.jpg' | relative_url }}" alt="李晨宇">
    </div>

    <div class="member-info">
      <h1>李晨宇</h1>
      <p><strong>2026级硕士生</strong></p>
      <p>科技楼北315</p>
    </div>
  </div>

  <hr>

  <h2>个人简介</h2>

  <p>
  大家好，我是李晨宇。我目前专注于磁畴物理的动力学仿真，研究工作围绕亚铁磁体系的磁畴壁动力学展开，主要通过vampire微磁学仿真等方法，研究亚铁磁体系的磁学性质，揭示畴壁运动的微观机理。未来希望进一步精进仿真技能，结合模拟与实验，为设计新型磁性器件与磁性材料提供见解。
  </p>

  <h2>研究方向</h2>

  <ul>
    <li>磁畴物理的动力学仿真</li>
    <li>亚铁磁体系的磁畴壁动力学</li>
    
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
