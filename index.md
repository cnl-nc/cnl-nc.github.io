---
layout: home
title: Computer Network Laboratories
subtitle: 東京大学 情報基盤センター ネットワーク研究部門 研究室
top_image: /assets/images/trip2026.jpg
---


## Welcome to CNL
 
学生の皆さんへ

大学院では研究が中心となり、その活動の主な場所は研究室となります。

[東京大学 情報基盤センターのネットワーク研究部門](https://www.itc.u-tokyo.ac.jp/network/)には、工藤研究室、関谷研究室、中山研究室、佐藤研究室、小川研究室、中村研究室、近藤研究室の７研究室があり、常日頃研究に取り組んでいます。この研究部門の特徴の一つは教員の多様さで、具体的な研究テーマ、過去の所属組織（大学・企業等）、積極的に参画している学会・研究会、センター外の共同研究先、兼務している学内外の業務等、実に様々です。もちろん、現場に強く、実践能力に優れている等の共通点もあります。このような教員と一緒に研究に取り組むことによって、研究の深さ・幅の両面で大きなメリットが得られます。

是非、研究に対する目的意識を明確に持って全力で取り組むことによって、研究の本質を体験し、楽しさ・苦しさの両面をしっかり味わい、充実した日々を送って欲しいと願っています。




## Faculty

<div class="table-wrap">
<table class="member-table faculty-table">
  <thead>
    <tr><th>氏名</th><th>職位</th><th>所属</th><th>研究室ホームページ</th></tr>
  </thead>
  <tbody>
  {%- for m in site.data.members.faculty %}
    <tr>
      <td class="name">{{ m.name }}</td>
      <td>{{ m.position }}</td>
      <td>
        {%- for a in m.affiliation %}
          {%- assign a_url = m.affi_url[forloop.index0] %}
          {%- if a_url %}<a href="{{ a_url }}">{{ a }}</a>{% else %}{{ a }}{% endif %}
          {%- unless forloop.last %} / {% endunless %}
        {%- endfor -%}
      </td>
      <td>{% if m.url %}<a href="{{ m.url }}">{{ m.url }}</a>{% endif %}</td>
    </tr>
  {%- endfor %}
  </tbody>
</table>
</div>

## Students

<div class="table-wrap">
<table class="member-table student-table">
  <thead>
    <tr><th>氏名</th><th>研究室</th><th>所属</th><th>Since</th></tr>
  </thead>
  <tbody>
  {%- for m in site.data.members.students %}
    <tr>
      <td class="name">{{ m.name }}</td>
      <td>{{ m.lab }}</td>
      <td>{{ m.affiliation }}</td>
      <td>{{ m.since }}</td>
    </tr>
  {%- endfor %}
  </tbody>
</table>
</div>


## Access

ネットワーク研究部門の研究室は、学生居室や会議室などのファシリティを共有しています。学生の居室は柏2キャンパスと弥生キャンパスの2箇所にあります。

* 東京大学 柏2キャンパス 情報基盤センター

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3232.180116541435!2d139.9447714!3d35.89360409999999!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60189eaaf172fe97%3A0x2ea2affb8658a6dc!2z5p2x5Lqs5aSn5a2mIOaDheWgseWfuuebpOOCu-ODs-OCv-ODvA!5e0!3m2!1sja!2sjp!4v1791965943548!5m2!1sja!2sjp" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>

<br/>

* 東京大学 弥生キャンパス 総合研究棟

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d686.9319969992716!2d139.76007914749957!3d35.71569490111222!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188c3188bbb81f%3A0xce6df915089abd8a!2z44CSMTEzLTAwMzIg5p2x5Lqs6YO95paH5Lqs5Yy65byl55Sf77yR5LiB55uu77yRIOe3j-WQiOeglOeptuajnw!5e0!3m2!1sja!2sjp!4v1791966039835!5m2!1sja!2sjp" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="strict-origin-when-cross-origin"></iframe>
