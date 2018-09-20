---
layout: page
title: Buku Siswa
permalink: /buku-siswa/
---

ArtiPedia mempublikasikan Buku Sekolah Elektronik bertujuan untuk menyebarkan buku pembelajaran dalam bentuk digital untuk semua jenjang pendidikan: SD, SMP, SMA dan SMK yang merupakan program dari Departemen Pendidikan Nasional Indonesia.

Setiap buku yang terdapat di [Artipedia](https://artipedia.site "ArtiPedia") telah dibeli hak ciptanya secara resmi oleh Departemen Pendidikan Nasional dari penulis atau penerbit yang terkait, yang untuk selanjutnya, buku - buku tersebut diubah dalam bentuk buku digital (ebook).

Dengan mengunduh <acronym title="Buku Sekolah Elektronik">BSE</acronym> ini dan menyimpannya di smartphone, tablet atau laptop; maka seluruh pelajar Indonesia dapat belajar dimana saja dan kapan saja. Bukan tidak mungkin jika daerah-daerah pelosok Indonesia yang distribusi buku sekolahnya kurang lancar, tetap dapat belajar sesuai standart pendidikan nasional. Para guru dapat memanfaatkan aplikasi ini untuk tetap memberikan pembelajaran yang dibutuhkan para siswanya.

Setiap buku yang ada dipublikasikan disini disediakan secara lengkap sesuai kebutuhan dasar pendidikan dan pelajaran Indonesia, dan yang memenuhi standard nasional pendidikan.

<ol class="arti">{% for post in site.categories.siswa %}
<li class="{% if page.title == post.title %}current{% endif %}">
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ol>

