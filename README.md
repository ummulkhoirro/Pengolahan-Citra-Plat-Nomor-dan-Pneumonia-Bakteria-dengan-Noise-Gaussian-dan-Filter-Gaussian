# Deskripsi
Proyek ini melakukan pengolahan citra pada dua jenis gambar: Plat Nomor dan Pneumonia Bakteria. Proses pengolahan meliputi penambahan noise Gaussian dan penerapan filter Gaussian untuk mengurangi noise tersebut. Pengolahan ini juga dievaluasi menggunakan dua metrik utama: Mean Squared Error (MSE) dan Peak Signal-to-Noise Ratio (PSNR).

## Langkah - langkah 
1. Menambahkan Noise Gaussian: Noise Gaussian ditambahkan pada gambar asli untuk mensimulasikan gangguan pada gambar.
2. Penerapan Filter Gaussian: Filter Gaussian diterapkan untuk mengurangi noise pada gambar.
3. Evaluasi Kualitas Gambar: Perbandingan antara gambar asli dan gambar yang telah difilter dilakukan menggunakan MSE dan PSNR untuk menilai kualitas hasil pengolahan gambar.

## Output
Output yang dihasilkan berupa tiga gambar untuk setiap dataset:

- Gambar Asli
- Gambar dengan Noise Gaussian
- Gambar setelah diterapkan filter Gaussian

Selain itu, hasil perhitungan MSE dan PSNR juga ditampilkan untuk menunjukkan efektivitas filter dalam mengurangi noise.
