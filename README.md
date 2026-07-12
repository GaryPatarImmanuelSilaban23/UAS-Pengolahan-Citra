# UAS-Pengolahan-Citra

# Project UAS Pengolahan Citra Digital (PCD)

Repository ini berisi source code, gambar hasil output, dan laporan tugas akhir pengganti UAS Praktikum mata kuliah Pengolahan Citra Digital. Topik yang dikerjakan pada project ini adalah **Geometrik Citra**.

## Identitas Mahasiswa
* **Nama:** Gary Patar Immanuel Silaban 
* **NIM:** 202431165
* **Kelas:** D
* **Mata Kuliah:** Pengolahan Citra Digital

## Deskripsi Project
Program ini dibuat menggunakan bahasa pemrograman Python di ekosistem Google Colab. Library utama yang dimanfaatkan adalah `OpenCV` (cv2) untuk komputasi matriks spasial citra, `NumPy` untuk operasi array, dan `Matplotlib` untuk visualisasi output berformat grid.

Operasi transformasi geometrik linear yang diaplikasikan pada citra masukan meliputi:
1. **Rotated:** Memutar matriks citra sebesar 45 derajat berlawanan arah jarum jam terhadap titik pusat gambar.
2. **Resized:** Merubah resolusi skala citra (downsampling) menjadi 50% dari dimensi aslinya.
3. **Cropped:** Memotong citra pada batas array 15% hingga 85% untuk mengekstraksi wilayah spesifik (Region of Interest).
4. **Flipped:** Membalikkan citra secara horizontal yang menghasilkan pencerminan lateral (sumbu X).
5. **Translated:** Menggeser matriks piksel sejauh 100 piksel ke arah sumbu X positif dan 100 piksel ke arah sumbu Y positif.

## Struktur File
* `UAS_PCD_202431165_Gary_D.ipynb` : File kodingan utama Python berbasis Jupyter Notebook.
* `20260712_210234.jpg` : File citra orisinal yang diakuisisi dari perangkat kamera (*Input*).
* `hasil_01_rotated.jpg` hingga `hasil_05_translated.jpg` : File ekstraksi citra setelah dikenai transformasi geometri (*Output*).
* `Laporan_UAS.pdf` : Dokumen laporan praktikum komprehensif.

## Cara Penggunaan
1. Clone repository ini atau unduh seluruh folder ke local machine Anda.
2. Buka file `.ipynb` menggunakan Jupyter Notebook atau unggah ke Google Colab.
3. Pastikan file gambar input (`20260712_210234.jpg`) berada di direktori (path) kerja yang sama dengan file kodingan.
4. Jalankan kode (Run all cells) secara berurutan dari atas ke bawah untuk mereplikasi hasil eksperimen.
