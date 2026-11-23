# GitHub Pages Loader — E-Sign CC Internal

File `index.html` menampilkan loader singkat lalu mengarahkan pengunjung ke Google Apps Script.

## Cara menggunakan
1. Buat repository GitHub baru, misalnya `esign-cc-loader`.
2. Upload `index.html` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.
6. Tunggu GitHub Pages menerbitkan situs. URL biasanya berbentuk:
   `https://USERNAME.github.io/esign-cc-loader/`

## Tujuan redirect
https://script.google.com/macros/s/AKfycbzufMXxDqvGYTYJWgne9jy9bWOiMIgykgfX36kLLc1qkoJMiQsCB2IPKVV8OgUmw4D7/exec

Untuk mengubah tujuan redirect, edit URL pada `index.html` di bagian meta refresh, JavaScript, dan tautan cadangan.
