---
layout: page
permalink: /people/
title: 科研团队
description: our team
nav: true
nav_order: 4

groups:
  - title: 课题组负责人
    members:
      - id: Kaiming-Cai
        name: 蔡凯明
        name_en: Kaiming Cai
        role: 教授
        note: 35岁以下科技创新35人
        email: 
        image: prof_pic.jpg
        link: https://hustami.github.io/teamweb/cv/

  - title: 教师
    members:
      - id: Tianli-Jin
        name: 靳田丽
        name_en: Tianli Jin
        role: 讲师
        email: 
        image: prof_jin.png
        link: https://hustami.github.io/teamweb/cv2/
  
  - title: 博士后
    members:
      - id: zyq
        name: 周钰卿
        role: 博士后
        image: zyq.jpg


  - title: 博士生
    members:
      - id: zyl
        name: 朱玉良
        role: 2024级博士生
        image: zyl.jpg

      - id: srp
        name: 石瑞鹏
        role: 2024级博士生
        image: srp.jpg

      - id: yzz
        name: 叶壮壮
        role: 2025级博士生
        image: yzz.jpg
        
      - id: hsh
        name: 侯绍华
        role: 2025级博士生
        image: hsh.jpg
        
      - id: wdh
        name: 吴帝桦
        role: 2025级直博生
        image: wdh.jpg

      - id: ljx
        name: 刘嘉新
        role: 2026级直博生（已推免录取）
        image: ljx.jpg
        
      - id: gzb
        name: 高梓博
        role: 2026级直博生（已推免录取）
        image: gzb.jpg

      


  - title: 硕士生
    members:
      - id: hjm
        name: 华俊茂
        role: 2024级硕士生
        image: hjm.jpg
     
      - id: gzq
        name: 高卓祺
        role: 2025级硕士生
        image: gzq.jpg
        
      - id: jsj
        name: 蒋叔稷
        role: 2025级硕士生
        image: jsj.jpg
      
      - id: wbx
        name: 王炳轩
        role: 2026级硕士生（已推免录取）
        image: wbx.jpg

      - id: szh
        name: 宋仔豪
        role: 2026级硕士生（已推免录取）
        image: szh.jpg

      - id: lcy
        name: 李晨宇
        role: 2026级硕士生（已推免录取）
        image: lcy.jpg


  - title: 已毕业学生
    collapsible: true
    members:
      - id: whp
        name: 王皓鹏
        role: 硕士（2023-2026）
        image: whp.jpg
        note: 毕业去向：北京熵旋芯智有限公司

      - id: sk
        name: 石坤
        role: 本科生（2024-2025）
        image: sk.jpg
        note: 毕业去向：美国伊利诺伊大学香槟分校攻读博士
---

<div class="lab-members-page">

  {% for group in page.groups %}

    {% if group.collapsible %}
    <details class="lab-section lab-collapsible-section">
      <summary class="lab-section-title lab-section-summary">
        {{ group.title }}
      </summary>
    {% else %}
    <section class="lab-section">
      <h2 class="lab-section-title">{{ group.title }}</h2>
    {% endif %}

      <div class="lab-grid {% if group.members.size == 1 %}lab-grid-one{% endif %}">

        {% for member in group.members %}

          {% if member.link %}
            {% assign card_url = member.link %}
          {% else %}
            {% assign card_url = '/people/' | append: member.id | append: '/' | relative_url %}
          {% endif %}

          <a class="lab-card" href="{{ card_url }}" aria-label="查看{{ member.name }}详细信息">

            <div class="lab-photo-box">
              <img src="{{ '/assets/img/members/' | append: member.image | relative_url }}" alt="{{ member.name }}">
            </div>

            <div class="lab-info">
              <div class="lab-name-cn">{{ member.name }}</div>

              {% if member.name_en %}
              <div class="lab-name-en">{{ member.name_en }}</div>
              {% endif %}

              <div class="lab-divider"></div>

              <div class="lab-role">{{ member.role }}</div>

              {% if member.note %}
              <div class="lab-note">{{ member.note }}</div>
              {% endif %}
            </div>

          </a>

        {% endfor %}

      </div>

    {% if group.collapsible %}
    </details>
    {% else %}
    </section>
    {% endif %}

  {% endfor %}

</div>


<style>
.lab-members-page {
  margin-top: 1.5rem;
}

.lab-section {
  margin-bottom: 2.2rem;
}

.lab-section-title {
  font-size: 1rem;
  font-weight: 700;
  color: #006eb8;
  border-top: 1px dashed #cfcfcf;
  padding-top: 0.75rem;
  margin-bottom: 1rem;
}

.lab-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(230px, 1fr));
  gap: 1rem;
}

.lab-grid-one {
  grid-template-columns: minmax(260px, 330px);
}

.lab-card {
  position: relative;
  display: grid;
  grid-template-columns: 105px 1fr;
  column-gap: 0.75rem;
  min-height: 150px;
  padding: 0.75rem;

  background: var(--global-card-bg-color);
  border: 1px solid var(--global-divider-color);
  border-radius: 0.25rem;
  box-shadow: 0 3px 8px rgba(0, 0, 0, 0.12);
}

.lab-photo-box img {
  width: 95px;
  height: 120px;
  object-fit: cover;
  border-top: 1px solid #e0e0e0;
}

.lab-info {
  text-align: center;
  padding-top: 0.25rem;
  padding-right: 0.25rem;
}

.lab-name-cn {
  font-size: 1rem;
  font-weight: 700;
  color: #111;
}

.lab-name-en {
  font-size: 0.8rem;
  font-weight: 600;
  color: #111;
  margin-top: 0.15rem;
}

.lab-divider {
  width: 100%;
  height: 0;
  border-top: 3px solid var(--global-divider-color);
  background: none;
  margin: 0.75rem 0 0.65rem;
}

.lab-role {
  font-size: 0.85rem;
  color: #333;
}

.lab-note {
  font-size: 0.78rem;
  color: #333;
  margin-top: 0.25rem;
  line-height: 1.35;
}

.lab-email {
  position: absolute;
  left: 0.55rem;
  bottom: 0.35rem;
  font-size: 0.75rem;
  color: #2c5e8b;
  text-decoration: none;
}

.lab-more {
  position: absolute;
  right: 0.55rem;
  bottom: 0.45rem;
  width: 20px;
  height: 20px;
  line-height: 17px;
  text-align: center;
  border-radius: 5px;
  background: linear-gradient(#3da1d9, #1c6095);
  color: #ffffff !important;
  font-size: 1.25rem;
  font-weight: 700;
  text-decoration: none;
}

.lab-more:hover {
  filter: brightness(1.1);
  text-decoration: none;
}

html[data-theme="dark"] .lab-card {
  background: var(--global-card-bg-color);
  border-color: var(--global-divider-color);
  box-shadow: 0 3px 8px rgba(0, 0, 0, 0.35);
}

html[data-theme="dark"] .lab-name-cn,
html[data-theme="dark"] .lab-name-en,
html[data-theme="dark"] .lab-role,
html[data-theme="dark"] .lab-note {
  color: #eeeeee;
}

@media (max-width: 900px) {
  .lab-grid {
    grid-template-columns: repeat(2, minmax(230px, 1fr));
  }
}

@media (max-width: 600px) {
  .lab-grid,
  .lab-grid-one {
    grid-template-columns: 1fr;
  }

  .lab-card {
    grid-template-columns: 95px 1fr;
  }

  .lab-photo-box img {
    width: 85px;
    height: 110px;
  }
}
  .lab-section-summary {
  cursor: pointer;
  list-style: none;
  user-select: none;
  position: relative;
  padding-left: 1.2rem;
}

.lab-section-summary::-webkit-details-marker {
  display: none;
}

.lab-section-summary::before {
  content: "▶";
  position: absolute;
  left: 0;
  top: 0.75rem;
  font-size: 0.75rem;
  color: #006eb8;
}

.lab-collapsible-section[open] .lab-section-summary::before {
  content: "▼";
}

.lab-collapsible-section:not([open]) {
  margin-bottom: 2.2rem;
}

.lab-collapsible-section:not([open]) .lab-section-summary {
  margin-bottom: 0;
}

.lab-collapsible-section[open] .lab-grid {
  margin-top: 1rem;
}
</style>
