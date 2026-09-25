K1

Error disebabkan karena kurangnya tanda titik koma (;) setelah variabel `int nilai = 80`. Dalam bahasa C++, setiap perintah harus diakhiri dengan tanda titik koma.

K2

1. Variabel yang dibuat bernama `nilai`, tetapi pada bagian output menggunakan `Nilai`. C++ membedakan huruf besar dan kecil, sehingga `nilai` dan `Nilai` dianggap berbeda.

2. Variabel `bonus` digunakan dalam program, tetapi belum didefinisikan sebelumnya sehingga menyebabkan error.

K3

Variabel `total` memiliki nilai 240. Jika 240 dibagi dengan jumlah mahasiswa yang bernilai 0, maka akan terjadi pembagian dengan nol. Seharusnya ada validasi agar jumlah mahasiswa tidak boleh 0 sebelum dilakukan pembagian.

K4

Kode tersebut tidak menghasilkan error, tetapi terdapat kesalahan pada hasil perhitungannya. Bilangan bulat yang dibagi dengan bilangan bulat akan menghasilkan bilangan bulat sehingga angka desimal bisa hilang. Seharusnya menggunakan `3.0` agar hasil pembagian dapat berupa bilangan desimal.

Menurut saya, kesalahan yang paling fatal adalah kesalahan sintaks dan logika. Kode bisa saja terlihat benar ketika dilihat, tetapi setelah dijalankan dan diuji, ternyata dapat menghasilkan error atau hasil yang tidak sesuai.
