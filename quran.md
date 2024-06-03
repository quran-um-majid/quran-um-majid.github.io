---
layout: page
title: Quran
permalink: /quran/
---

{% for item in site.data.quran-um-majid %}
  <h2>{{ item.surat_nomor }}:{{ item.ayat_nomor }}</h2>
  <!-- <p class="quran">{{ item.teks_ar }}</p> -->
  <p>{{ item.teks_id }}</p>
{% endfor %}