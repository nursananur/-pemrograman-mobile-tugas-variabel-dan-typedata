Nama : Nursan Anur 
Npm : 07352311123

Deskripsi Program

1. Input Data dari User
Nama → diinput sebagai String.
Jam Kerja per Minggu → harus lebih dari 0 (int).
Upah per Jam → harus lebih dari 0 (double).
Status Karyawan → hanya bisa "tetap" atau "kontrak".
Jika tetap, maka statusKaryawan = true.
Jika kontrak, maka statusKaryawan = false.

2. Perhitungan Gaji
Gaji Kotor = jamKerjaPerMinggu * upahPerJam.
Pajak =
10% jika karyawan tetap.
5% jika karyawan kontrak.
Gaji Bersih = Gaji Kotor - Pajak.
Output Slip Gaji

3. Output Slip Gaji:
Nama
Jam kerja
Upah per jam
Status karyawan
Gaji kotor
Pajak
Gaji bersih setelah pajak

4. Alur Jalannya Program
Program akan menanyakan Nama → user isi, misalnya Budi.
Program akan menanyakan Jam Kerja per Minggu → jika diisi 0 atau negatif, program meminta ulang.
Program akan menanyakan Upah per Jam → jika diisi 0 atau negatif, program meminta ulang.
Program akan menanyakan Status Karyawan → hanya bisa tetap atau kontrak.
Setelah semua data valid, program menghitung gaji dan mencetak Slip Gaji ke layar.

5. Cara Menjalankan Program
Karena ini bahasa Dart, kita butuh SDK Dart atau bisa juga pakai Visual Studio Code + Dart extension.
Langkah-langkah:
Install Dart SDK
Download dari https://dart.dev/get-dart.
Pastikan sudah bisa dipanggil di terminal
contohnya: dart --version
Simpan program dengan nama misalnya slip_gaji.dart.
Jalankan di terminal
contohnya: dart run slip_gaji.dart
atau
dart slip_gaji.dart

6. Contoh outputnya:
Masukkan Nama : Nursan
Jam kerja per minggu : 20
Upah per jam : 50000
Status karyawan (tetap/kontrak) : tetap

---Slip Gaji---
Nama: Nursan
Jam kerja per minggu: 20
Upah per jam: Rp50000.0
Status karyawan : Tetap
Gaji Kotor: Rp2000000.0
Pajak: Rp200000.0
Gaji Bersih (setelah pajak): Rp1800000.0

Kesimpulannya:
Program ini akan membuat slip gaji otomatis berdasarkan input user, lengkap dengan perhitungan pajak sesuai status karyawan.
