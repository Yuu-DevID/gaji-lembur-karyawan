# Program Gaji Karyawan

Aplikasi web sederhana untuk menghitung total gaji karyawan berdasarkan golongan dan jam lembur. Dikembangkan menggunakan HTML, CSS, dan JavaScript.

## Fitur Utama
- **Pemilihan Golongan Karyawan**:  
  Tiga pilihan golongan dengan gaji pokok berbeda:
  - Golongan A: Rp5.000.000
  - Golongan B: Rp6.500.000
  - Golongan C: Rp9.500.000

- **Perhitungan Lembur**:  
  Gaji lembur dihitung sebagai persentase dari gaji pokok berdasarkan jumlah jam lembur:
  - 1 jam → 30%
  - 2 jam → 32%
  - 3 jam → 34%
  - 4 jam → 36%
  - ≥5 jam → 38%

- **Tampilan Hasil**:  
  Menampilkan rincian gaji pokok, gaji lembur, dan total gaji dalam format Rupiah (IDR).

## Cara Menggunakan
1. Buka file `index.html` di browser web.
2. Pilih **Golongan Karyawan** dari menu dropdown.
3. Masukkan **jumlah jam lembur** (angka ≥ 0).
4. Klik tombol **"Hitung Gaji Total"**.
5. Hasil perhitungan akan muncul di bawah tombol.

## Validasi
Aplikasi memastikan:
- Golongan telah dipilih.
- Jam lembur diisi dengan angka valid (≥ 0).
- Menampilkan peringatan jika input tidak lengkap atau tidak valid.

## Struktur Proyek
