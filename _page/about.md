---
layout: page
title: About
menu: false
order: 10
---

{% assign author = site.data.authors[page.author] | default:site.data.authors.first[1] %}

<article class="page" role="article">
  <div class="author-body text-center">
  {% if author.picture %}
    {% include srcset-img.html img=author.picture alt=author.name %}
  {% endif %}
    <div class="author-body-description">
      {{ author.about | markdownify }}
    </div>
  </div>

<div markdown="1">
Jejalink ([Jejalink.com](https://jejalink.com/)) merupakan website media alternatif yang bisa kamu temukan di pencarian google dan beberapa pencarian di internet dengan cara mengetik "jejalink / jejalink.com / jejalinkcom".

Terbentuk sebagai media yang ingin menjadi mainstream karena sudah bosan menjadi indie, dengan ini semoga gacon.id dapat pula menjadi media berbasis online yang mampu memberikan informasi menarik bagi para peselancar dunia maya tentunya meski masih sebagai alternatif atau rujukan.

Seperti slogan jejalink.com "NAH" yang bermaksud bahwa pasti setiap orang pernah dan akan mencari informasi di internet, jejalink.com hidup memberikan jawaban alternatif "NAH" akhirnya kamu menemukannya di jejalink.com
</div>
