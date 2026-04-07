---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
author_profile: true
permalink: /
title: "About"
sitemap: true
toc: true
toc_label: "Content Table"
toc_sticky: true
redirect_from:
  - /about/
  - /about.html
description: "Shunqiang Feng's personal academic page, showcasing his background, research interests, and news."
---

I am Shunqiang FENG (冯顺强 in Chinese), a second-year Ph.D. student in the Department of Computer Science at the University of Virginia since Spring 2025. I am also a member of WINK (Wireless Intelligence & NetworKing) Lab and Link Lab under the supervision of [Prof. Kun Qian](https://kunqian.info).

My research focuses on Mobile Computing & Networking, Wireless Sensing, etc.

## 🎓 Education Background

- **University of Virginia**  
  _Ph.D. in Computer Science (2025 - )_
- **University of Electronic Science and Technology of China**  
  _B.Eng. in Electronic Information Engineering (2020 - 2024)_

## 📄 Selected Publications

- <span style="background-color:#1565C0; color:white; padding:1px 7px; border-radius:4px; font-size:0.82em; font-weight:bold;">MobiSys 2026</span> BeamFormer: Transformer-based Beam Management for 6G Networks [<a href="https://github.com/Shunqiang-Feng/BeamFormer">Code <i class="fab fa-github"></i></a>]  
  **Shunqiang Feng**, Swastik Kanjilal, Kun Qian, Ish Jain

## 🚀 Latest News

{% for post in site.posts | sort: 'date' | reverse | limit: 3 %}

- **[{{ post.date | date: "%Y-%m" }}]** {{ post.abstract }}

{% endfor %}

<div style="text-align: center;">
    <a href="/news/">Read more...</a>
</div>

## 🏆 Awards

- **Undergraduate**
  - Excellent Student Scholarship
  - National Encouragement Scholarship
  - Outstanding Graduate
  - Outstanding Graduation Thesis
