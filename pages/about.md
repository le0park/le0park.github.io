---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

안녕하세요:wave:, **{{ site.author.name }}** 입니다. <br>
상상을 현실로 만들기 위해 컴퓨터공학을 배우게 된 따끈따끈한:hotsprings: 개발자입니다. <br>
다양한 언어, 기술, 원리에 거부감이 적고 배우는 것을 좋아합니다.
음악도 클래식:musical_score:부터 힙합:minidisc:까지 가리지 않고 좋아합니다.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>