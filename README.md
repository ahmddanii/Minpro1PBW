# 🌐 Portfolio Website - Ahmad Dani

Website portofolio pribadi berbasis **HTML, CSS, Bootstrap 5, dan Vue JS** yang menampilkan informasi profil, keahlian, pengalaman, dan sertifikat dalam bentuk website statis yang responsif.

---
## 👨‍💻 Developed By

**Ahmad Dani**   
2409116074



## 📌 Deskripsi Project

Project ini merupakan website portofolio statis yang dibuat untuk memenuhi tugas Praktikum Pemrograman Aplikasi Bergerak (PAB).  

Website ini memiliki beberapa section utama yaitu:

- Home (Hero Section)
- About Me
- Skills (Progress Bar)
- Experience
- Certificates
- Navbar dan Footer

Website dibuat dengan tampilan modern, responsif, dan memanfaatkan Vue JS untuk membuat data dinamis meskipun tetap bersifat statis.

---

# 🏠 Tampilan Setiap Section / Fitur

## 1️⃣ Home (Hero Section)

Menampilkan:
- Nama
- Role / Profesi
- Foto profil

Menggunakan:
- Bootstrap Grid System (row, col-md)
- Flexbox (d-flex align-items-center)
- Vue Interpolation `{{ name }}` dan `{{ role }}`

---

## 2️⃣ About Me

Berisi:
- Deskripsi diri
- Minat di bidang Web Development, UI/UX, dan Networking

Menggunakan:
- Bootstrap container & grid
- Typography utilities
- Vue interpolation untuk nama dan role

---

## 3️⃣ Skills (Progress Bar)

Menampilkan daftar skill dalam bentuk progress bar.

Contoh skill:
- Public Speaking
- Programming
- Networking
- Teaching

Menggunakan:
- Bootstrap Progress Component
- Class dinamis Vue (`:class`)
- Binding style Vue (`:style`)
- Looping menggunakan `v-for`

Contoh kode:

```html
<div v-for="skill in skills" :key="skill.name">
  <div class="progress-bar"
       :class="skill.color"
       :style="{ width: skill.level + '%' }">
       {{ skill.level }}%
  </div>
</div>
```

# ⚙️ Teknologi yang Digunakan

<p align="center">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="60" height="60"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" width="60" height="60"/>
</p>

---

### 🔹 HTML5  
Digunakan sebagai struktur dasar website.

### 🔹 CSS3  
Digunakan untuk styling dan custom design.

### 🔹 Bootstrap 5  
Digunakan untuk layouting, grid system, dan komponen UI responsif.

### 🔹 Vue JS 3 (CDN)  
Digunakan untuk data binding, looping (`v-for`), dan interaktivitas.
## 📁 Struktur Project
```
Mini-Project1-PAB/
│
├── index.html
├── style.css
├── README.md
└── assets/
    └── img/
```
