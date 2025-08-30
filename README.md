Nama : Nursan Anur 
Npm : 07352311123

Deskripsi Program

Input Data dari User
Nama → diinput sebagai String.
Jam Kerja per Minggu → harus lebih dari 0 (int).
Upah per Jam → harus lebih dari 0 (double).
Status Karyawan → hanya bisa "tetap" atau "kontrak".
Jika tetap, maka statusKaryawan = true.
Jika kontrak, maka statusKaryawan = false.

Perhitungan Gaji
Gaji Kotor = jamKerjaPerMinggu * upahPerJam.
Pajak =
10% jika karyawan tetap.
5% jika karyawan kontrak.
Gaji Bersih = Gaji Kotor - Pajak.
Output Slip Gaji

Program menampilkan:
Nama
Jam kerja
Upah per jam
Status karyawan
Gaji kotor
Pajak
Gaji bersih setelah pajak

Alur Jalannya Program
Program akan menanyakan Nama → user isi, misalnya Budi.
Program akan menanyakan Jam Kerja per Minggu → jika diisi 0 atau negatif, program meminta ulang.
Program akan menanyakan Upah per Jam → jika diisi 0 atau negatif, program meminta ulang.
Program akan menanyakan Status Karyawan → hanya bisa tetap atau kontrak.
Setelah semua data valid, program menghitung gaji dan mencetak Slip Gaji ke layar.
