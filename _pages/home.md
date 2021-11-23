---
title: "COSMO'S Lib"
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.75"
  overlay_image: /assets/images/home-page-feature.jpg
excerpt: >
  과거에도 있었고 현재에도 있으며 미래에도 있을 그 모든 것
feature_row:
  - image_path: /assets/images/home-page-humanities.jpg
    alt:
    title: "인문/사회"
    excerpt: "인간의 가치와 인간만이 지닌 자기표현 능력을 바르게 이해하기 위한 학문 분야"
    url: "/tags/인문/"
    btn_class: "btn--primary"
    btn_label: "더 알아보기"
  - image_path: /assets/images/home-page-science.jpg
    alt:
    title: "과학"
    excerpt: "사물의 구조·성질·법칙 등을 관찰 가능한 방법으로 얻어진 체계적·이론적인 지식의 체계"
    url: "/tags/과학/"
    btn_class: "btn--primary"
    btn_label: "더 알아보기"
  - image_path: /assets/images/home-page-novel.jpg
    alt:
    title: "소설"
    excerpt: "사건을 미적으로 질서화하여 통일적인 의미가 구현될 수 있도록 산문으로 서술한 서사 문예"
    url: "/tags/소설/"
    btn_class: "btn--primary"
    btn_label: "더 알아보기"
  - image_path: /assets/images/home-page-history.jpg
    alt:
    title: "역사"
    excerpt: "인류 사회의 변천과 흥망의 과정, 지난 시대에 남긴 기록물, 이를 연구하는 학문 분야"
    url: "/tags/역사/"
    btn_class: "btn--primary"
    btn_label: "더 알아보기"
  - image_path: /assets/images/home-page-self-dev.jpg
    alt:
    title: "자기계발"
    excerpt: "자신의 능력, 적성 등에 있어서 강점과 약점을 찾고 확인하여 성장을 위한 기회로 활용하는 모든 활동"
    url: "/tags/자기계발/"
    btn_class: "btn--primary"
    btn_label: "더 알아보기"
  - image_path: /assets/images/home-page-economy.jpg
    alt:
    title: "정치/경제"
    excerpt: "생산, 매입과 매각 행위, 그리고 이들 행위들이 각각 법, 관습과 정부와 맺는 관계를 연구하는 학문"
    url: "/tags/정치-경제/"
    btn_class: "btn--primary"
    btn_label: "더 알아보기"
---
{% include feature_row %}

# 최근 글

{% for post in site.posts limit: 6 %}
  {% include archive-single.html %}
{% endfor %}