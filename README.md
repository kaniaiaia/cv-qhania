# CV Online - Qhania Husna Fadillah (versi HTML statis)

Website CV murni HTML + CSS + Bootstrap 5, tanpa PHP dan tanpa database,
sehingga bisa langsung dipublish gratis lewat **GitHub Pages**.

## Struktur
```
cv-qhania-html/
├── index.html
└── assets/
    ├── css/style.css
    └── img/profil.jpg   <- taruh foto kamu di sini (opsional)
```

## Cara publish ke GitHub Pages
1. Buka https://github.com/new, buat repository baru, misalnya `cv-qhania`, pilih **Public**.
2. Klik **uploading an existing file**, lalu seret **isi** folder ini
   (`index.html` dan folder `assets`) ke halaman upload. Pastikan `index.html` berada di
   paling atas repository, bukan di dalam subfolder. Klik **Commit changes**.
3. Buka tab **Settings** -> **Pages**.
4. Pada **Build and deployment**, pilih Source: **Deploy from a branch**,
   Branch: **main** dan folder **/ (root)**, lalu **Save**.
5. Tunggu 1-2 menit. Alamat CV kamu:
   `https://USERNAME.github.io/cv-qhania/`
   (ganti USERNAME dengan username GitHub kamu)

Tips: kalau repository diberi nama `USERNAME.github.io`, alamatnya jadi
`https://USERNAME.github.io/` tanpa nama repository.

## Mengubah isi CV
Buka `index.html` lalu cari bagian yang ingin diubah (setiap section diberi komentar).
Setelah diedit, upload ulang file tersebut ke GitHub dan halaman otomatis diperbarui.

Foto profil: simpan dengan nama `profil.jpg` di folder `assets/img/`.
Kalau file tidak ada, yang tampil lingkaran berinisial "QH".
