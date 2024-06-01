# Kepadatan Manusia di gerbong KAI
    Staf APKMGK (Asosiasi Pengendalian Kepadatan Manusia di Gerbong Kereta) sedang bekerja
untuk membuat statistik tentang berapa banyak orang yang menggunakan kereta sebagai moda
transportasi dan bagaimana mereka memilih gerbong untuk masuk. Mereka mencatat, dari
waktu ke waktu, berapa banyak orang yang masuk ke gerbong tertentu. Untuk menghasilkan
data yang bermanfaat, staf **perlu mengetahui** pada waktu tertentu **berapa banyak orang
berbeda yang berada dalam jarak dua gerbong**.
    Mereka membutuhkan bantuan Anda untuk mengetahui informasi tersebut secara cepat!
Untuk mengetahui informasi tersebut, Anda hanya diberikan spreadsheet dengan data **jumlah
gerbong N** (dari 1 ke N, dari kiri ke kanan), dan **M aktivitas** yang terjadi pada hari itu. 
### Catatan:
**Asumsikan awalnya semua gerbong kosong**.
## Jenis Aktifitas
Aktivitasnya bisa berupa tipe 1 atau tipe 2:
**1 X Y** - Artinya Y orang masuk ke gerbong X
**2 A B C D** - Artinya mereka ingin mengetahui jumlah orang berbeda di gerbong interval [A, B]
dan [C, D].
## Input dan Output
### Input
    Baris pertama berisi dua bilangan bulat **N dan M**. Setiap dari M baris berikutnya akan berisi
aktivitas tipe "1 X Y" **(1 ≤ X ≤ N dan 1 ≤ Y ≤ 100)** atau tipe 2 "2 A B C D" **(1 ≤ A, B, C, D ≤ N
dan A ≤ B dan C ≤ D)**, seperti yang sudah dijelaskan pada paragraf di atas.
### Output
    Untuk setiap aktivitas tipe 2, tampilkan jumlah total orang berbeda dalam interval yang
diberikan.
