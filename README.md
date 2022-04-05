# LATIHAN7DPBO2022


## Saya Muhamad Firmansyah 2010021 mengerjakan Latihan 7 DPBO dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin

Sebuah repository untuk mengunggah kodingan dari latihan dpbo 2022

1. Proses klik Add
![add](https://user-images.githubusercontent.com/99308745/161754340-47304b1e-7145-4308-976c-fc50bcf42068.gif)

Menambahkan fungsi pada task yaitu mengambil semua masukan input selanjutnya menggunakan proses query penambahan "SELECT * FROM td_to_do VALUES" ke database
didalam file index.php ditambahkan proses pengenalan masukan berupa button ADD menggunakan isset($_POST['add'])
lalu data ditampilkan

3. Proses klik Selesai
![update](https://user-images.githubusercontent.com/99308745/161754379-5105e536-69c6-4e86-b394-8f97cdc51389.gif)
Menambah fungsi update, dimana mengubah status yang semulanya belum menjadi sudah, dengan query "UPDATE tb_to_do set status" ke database
didalam file index.php ditambahkan proses pengenalan masukan berupa button SELESAI menggunakan isset($_GET['id_status'])

5. Proses klik Hapus
![delete](https://user-images.githubusercontent.com/99308745/161754360-077acbf6-4faa-42ef-8831-136fa2904ee6.gif)
Menambah fungsi delete, dimana mencari id dari data yang ingin dihapus lalu panggil query "DELETE FROM tb_to_do where id = $id" dari database
didalam file index.php ditambahkan proses pengenalan masukan berupa button SELESAI menggunakan isset($_GET['id_status'])

TAMBAHAN
1.Proses Sorting
![sort](https://user-images.githubusercontent.com/99308745/161754411-c308c587-b985-4147-995f-25d388a2923e.gif)
menggunakan query yang sama dengan get task namun ditambahkan kode order by diakhir query berdasarkan sortingan yang diinginkan
