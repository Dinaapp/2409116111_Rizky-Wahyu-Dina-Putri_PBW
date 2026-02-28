### Nama: Rizky Wahyu Dina Putri
### NIM: 2409116111

# PERSONAL PORTOFOLIO WEBSITE

## Deskripsi

## Teknologi Yang Digunakan
### 1. HTML 5
Digunakan sebagai struktur dasar dari halaman web
### 2. CSS
Digunakan untuk membuat animasi, mengatur tata letak (margin, position, dll), background dari website, font size dan lain lain.
### 3. Bootstrap
Digunakan untuk membantu dalam layouting, pada website menggunakan bootstrap pada bagian navbar, grid system dan card pada sertifikat, carousel pada pengalaman.
### 4. Vue JS 
Digunakan untuk membuat tampilan lebih interaktif dan dinamis.
### 5. Google fonts
Menggunakan 2 jenis fonts yaitu Cormorant Garamond untuk judul dan nama yang aesthetic dan poppins untuk teks body.
## Code, Tampilan, dan penjelasan Setiap Section
### Navbar
<img width="1888" height="174" alt="image" src="https://github.com/user-attachments/assets/baaf3c86-b854-42e6-8362-cc322d4a0e55" />
```html
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg fixed-top glass-nav">
        <div class="container">
            <a class="navbar-brand fw-bold text-white" href="#">Rizky Wahyu Dina Putri </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="nav nav-tabs ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" :class="{ active: currentSection === 'home' }"
                        aria-current="page" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" :class="{ active: currentSection === 'about' }"
                        href="#about">About Me</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" :class="{ active: currentSection === 'certificates' }"
                        href="#certificates">Certificates</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
```
Saat website dijalankan, pada bagian atas website terdapat navbar transparant sedikit buram yang tetap terlihat meski layar sudah di scroll. Di navbar terdapat nama "Rizky wahyu dina putri" di sebelah kiri, dan di sebelah kanan terdapat 3 tab navigasi, yaitu home, about me, dan certificates yang mewakili section di web.


