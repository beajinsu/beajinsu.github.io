---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Economics, The Ohio State University**, 2020  
  *(Advisor: John H. Kagel)*
* **M.A. in Economics, The Ohio State University**, 2015
* **M.A. in Economics, Yonsei University**, 2014
* **B.A. in Economics, Yonsei University**, *Magna Cum Laude*, 2012

Work experience
======
* **Korea Institute of Finance**,  2024 – present
  * Associate Research Fellow

* **Korea Institute of Public Finance**,  2020 – 2024  
  * Associate Research Fellow
  * Team Manager, Fiscal System Analysis Team

* **KEPCO Economy & Management Research Institute**, 2013 – 2014  
  * Junior Researcher
  * long-term electricity demand estimation team

<!-- 자동으로 모아서 보여주는 방식 -->

Journal Publications
======
<!-- ─────────────── Publications (특정 카테고리만) ─────────────── -->
{% comment %}
  보여줄 카테고리 목록을 파이프(|)로 구분해 한 줄에 적습니다.
  필요에 따라 마음대로 추가 · 삭제하세요.
{% endcomment %}

{% assign cv_pub_cats = "manuscripts|other_pubs|books" | split:"|" %}
  <ul>
  {% for post in site.publications reversed %}
    {% unless cv_pub_cats contains post.category %}{% continue %}{% endunless %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
* 2025 제 3회 기후재정포럼 세미나 : 기후재정, 어떻게 조달할 것인가 [매거진한경](https://magazine.hankyung.com/business/article/202509117659b)
* 2025 제5차 지속가능경제 정책협의회 [한국경제](https://www.hankyung.com/article/202505204470i) 
* 2024 재생에너지 생산·사용 활성화 심포지엄 [세정신문](https://www.taxtimes.co.kr/news/article.html?no=264890)
* 2023 Australia-Korea Tax Symposium, Seoul, Republic of Korea
* 2023 Asia-Pacific Economic Science Association Meeting, Seoul, Republic of Korea
* 2021 Annual Society for the Advancement of Economic Theory Conference, Seoul, South Korea
* 2021 Korea’s Allied Economic Associations Annual Meeting
* 2019 Economic Science Association North American Meeting, Los Angeles, CA
* 2019 Nanjing International Conference on Game Theory
* 2019 Stony Brook International Conference on Game Theory, Stony Brook, NY
* Summer School of Econometric Society in Singapore, 2018
* 2018 Midwest Economic Association Annual Meeting, Evanston, IL
* 2018 Annual International Industrial Organization Conference, Indianapolis, IN
* 2017 Economic Science Association North American Meeting, Richmond, VA
  
Teaching
======
  <ul>
  {% for post in site.teaching reversed %}
    {% if post.hidden %}{% continue %}{% endif %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
  
Service and leadership
======
* Refereeing
  * Eastern Economic Journal
  * Telecommunications Policy
  * Journal of Economics & Management Strategy
  * Social Choice and Welfare
  * The Korea Local Administration Review (지방행정연구)
  * Journal of Institutional and Theoretical Economics