# Refleksi Pengerjaan Modul 1: Dasar Web

**Nama:** Callista Rahma Putri  
**NIM:** 251511004  
**Kelas:** D3 Teknik Informatika-1A  

---

### Refleksi Proses dan Pembelajaran

Pengerjaan praktikum Modul 1 ini memberikan pemahaman mendalam mengenai pentingnya pemisahan antara struktur dokumen semantik (HTML) dan lapisan presentasi visual (CSS). Pada Task 1, saya belajar bahwa penggunaan tag semantik seperti `<nav>`, `<section>`, dan `<footer>` bukan sekadar pengganti `<div>`, melainkan cara memberikan konteks hierarki informasi yang bermakna bagi mesin pencari maupun teknologi pembaca layar (aksesibilitas).

Tantangan utama yang saya hadapi muncul saat memasuki Task 2 dan Task 3, yaitu ketika menerapkan sistem *design tokens* berbasis CSS Custom Properties. Sempat terjadi kendala di mana palet warna yang telah ditentukan (Blue `#C4DAE8`, Butter `#FEEFB8`, dan Chocopie `#432F2E`) tidak muncul di peramban dan tampilan halaman menjadi putih polos[cite: 8, 9]. Melalui proses *debugging* menggunakan panel DevTools, saya menemukan bahwa nama variabel pada file `variables.css` tidak sinkron dengan pemanggilan variabel di file `style.css'. Selain itu, perubahan kode sempat belum tersimpan sepenuhnya sebelum diuji pada Live Server. Kendala ini diselesaikan dengan menyelaraskan seluruh penamaan token warna dan memastikan pemanggilan tautan stylesheet terurut dengan benar

Pada Task 3, penerapan pendekatan *mobile-first* membantu saya memahami cara kerja Flexbox dan Box Model. Penggunaan aturan global `box-sizing: border-box` terbukti krusial dalam mencegah masalah *overflow* horizontal saat halaman diakses pada resolusi sempit seperti 320 px. Dengan menetapkan *breakpoint* berbasis kebutuhan konten pada lebar 768 px, navigasi dan komponen kartu profil dapat bertransisi secara luwes dari tumpukan vertikal menjadi tata letak mendatar yang nyaman dipandang.

Secara keseluruhan, pengerjaan modul ini melatih ketelitian saya dalam menyusun kode yang bersih (*clean code*), modular, serta mematuhi standar aksesibilitas keyboard melalui penyediaan umpan balik visual `:focus-visible`