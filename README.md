# labpy5
* Buat program sederhana yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan :
* Program dibuat dengan menggunakan Dictionary
* Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data, Tampilkan Data, Cari Data)
* Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%, uts: 35%, uas: 35%)
* Buat flowchart dan penjelasan programnya pada README.md.
* Commit dan push repository ke github.

# Flowchart 

![Tanpa judul](https://user-images.githubusercontent.com/58107014/71773365-64218000-2f8e-11ea-9398-92676bec1df7.png)

# Penjelasan

1. daftar = {} Berikut adalah dictionary yang di definisikan terlebih dahulu.
2. while True: Berikut adalah perulangan yang digunakan.
3. Keluar

* if perintah.lower() == 'k':
* Perulangan di atas adalah perulangan yang akan berjalan terus menerus, dan akan berhenti jika kode berikut di eksekusi.

# Output
![Tanpa judul2](https://user-images.githubusercontent.com/58107014/71773416-54566b80-2f8f-11ea-92e1-08ffa52628c9.png)
4. Jika k di input dan lower() digunakan untuk mengkonversi input yang dimasukan ke bentuk lower case dan Input k digunakan berdasarkan perintah yang sudah di masukan dalam keterangan pada fungsi input di bawah ini :
![Tanpa judul3](https://user-images.githubusercontent.com/58107014/71773451-d8105800-2f8f-11ea-942a-50483968a6d1.png)
# Output
![Tanpa judul4](https://user-images.githubusercontent.com/58107014/71773467-2160a780-2f90-11ea-82a9-70772e9a83f9.png)
5. Input data
* berikut digunakan untuk melakukan input data seperti Nama, NIM, Nilai Tugas, UTS dan UAS :
![Tanpa judul5](https://user-images.githubusercontent.com/58107014/71773506-9cc25900-2f90-11ea-926b-ebf9b21f38f6.png)
* Untuk nilai akhir n_akhir, di buat berdasarkan operasi dari variabel n_tugas, n_UTS dan n_UAS yang mewakili Nilai Tugas, UTS dan UAS.
# Output
![Tanpa judul6](https://user-images.githubusercontent.com/58107014/71773522-004c8680-2f91-11ea-88a1-3592c4be7359.png)
6. Melihat data
* Selanjutnya adalah kode yang digunakan untuk melihat input yang sudah dimasukan :
![Tanpa judul7](https://user-images.githubusercontent.com/58107014/71773541-3d187d80-2f91-11ea-9a39-5e1b93048c0b.png)
* Data dalam perulangan for di ambil dari variabel dictionary daftar pada bagian value yang berbentuk list. variabel no diguanakan untuk membuat nomor. Data yang akan ditampilkan adalah Nama, NIM, Nilai Tugas, UTS, UAS, dan Nilai Akhir.
# Output
![Tanpa judul8](https://user-images.githubusercontent.com/58107014/71773557-810b8280-2f91-11ea-8ff7-8739ea1f33a8.png)
7. Mengubah data
* Perintah dijalankan jika input yang di masukan adalah u, di dalam kondisi ini terdapat input dan kondisi, dimana jika input nama ada di dalam variabel daftar.keys maka akan muncul beberapa pilihan untuk mengubah semua data atau data tertentu saja.

* Selanjutnya adalah kode yang digunakan untuk menggubah input yang sudah dimasukan :
![Tanpa judul9](https://user-images.githubusercontent.com/58107014/71773575-df386580-2f91-11ea-96b3-e87f2e34ac65.png)
* Berikut kondisi yang digunakan untuk memasukan pilihan :
![Tanpa judul10](https://user-images.githubusercontent.com/58107014/71773592-1575e500-2f92-11ea-8af5-51bbfecb4e67.png)
# Output
![Tanpa judul11](https://user-images.githubusercontent.com/58107014/71773620-71406e00-2f92-11ea-8043-6adfc60d7f91.png)
8. Mencari Data
* Perbandingan untuk mencari data yang akan diubah sama seperti cara mengubah data, hanya saja perintah ini digunakan untuk menampilkan data yang di input berdasarkan nama.

* Berikut bagaimana mencari data yang sudah di inputkan sebelumnya :
![Tanpa judul12](https://user-images.githubusercontent.com/58107014/71773640-c1b7cb80-2f92-11ea-9c8d-26f1555f144a.png)
# Output
![Tanpa judul13](https://user-images.githubusercontent.com/58107014/71773655-004d8600-2f93-11ea-84b0-8743db18eb75.png)
9. Menghapus data
* Sama seperti mengubah dan mencari data, untuk menghapus data yang dipilih :
![Tanpa judul14](https://user-images.githubusercontent.com/58107014/71773660-37bc3280-2f93-11ea-816c-3985a979950b.png)
* Data yang di hapus adalah data yang di input dalam variabel nama dimana berisi nama (string) yang mewakili data NIM, Nilai Tugas, UTS dan UAS.

# Output
![Tanpa judul15](https://user-images.githubusercontent.com/58107014/71773684-9681ac00-2f93-11ea-9c95-e1e56006bbd9.png)








