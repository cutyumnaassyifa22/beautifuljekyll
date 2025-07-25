---
layout: default
title: Home
---

# Halo, saya Cut Yumna!

Selamat datang di blog portofolio saya.  
Website ini dibuat sebagai tugas remedial menggunakan **Jekyll** dan **GitHub Pages**.

![Profil](assets/img/profile.jpg)

---

## ✨ Tentang Saya
Saya adalah mahasiswa Politeknik Negeri Lhokseumawe jurusan D4, dan ini adalah project web statis saya menggunakan Jekyll.

---

## 📝 Postingan Terbaru
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%d %B %Y" }}
{% endfor %}
