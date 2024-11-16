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

I am Shunqiang **FENG** (**冯** 顺强 in Chinese), an incoming PhD student in the **Computing Science** Department of **University of Virginia**, starting in the Spring 2025. I am also a member of **WI4X (Wireless-Intelligence-For-Everything)** Lab under the supervision of **[Prof. Kun Qian](https://kunqian.info)**.

My research focuses on **Mobile Computing & Networking**, **Wireless Sensing**, etc.

Currently, I am conducting remote research under the guidance of Prof. Qian.

## 🎓 Education Background

- **University of Virginia**  
  _PhD in Computer Science (2025 - )_
- **University of Electronic Science and Technology of China**  
  _BEng in Electronic Information Engineering (2020 - 2024)_

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
