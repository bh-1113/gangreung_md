---
layout: page
title: GangReung 여행 블로그
---

# 🌊 하루 여행 코스
강릉의 바다, 커피, 맛집까지 완벽한 힐링 여행을 소개합니다.

---

## 📝 최신 여행기
<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
