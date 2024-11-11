Nama : Dea Cipta Ningrum Aimanta Putri
-
Kelas : 2A TRPL 
-

1. Praktikum 1
   ![Screenshot (1268)](https://github.com/user-attachments/assets/4df0e17a-bc8f-4432-9920-2f81e3821153)

3. Praktikum 2

   ![Screenshot (1274)](https://github.com/user-attachments/assets/e6f1794b-f98f-4d9e-be69-d3ad8986a772)


**TUGAS PRAKTIKUM 1**
- 
2. Langkah 4 bertujuan untuk membuat akses yang digunakan untuk mengimpor model data. Apabila tidak dilakukannya export, maka setiap model seperti plan, task harus diimport secara terpisah di setiap yang membutuhkan model-model tersebut. jadi ketika tidak adanya file data_layer yang mengeskpor model, perlu menulis semua import di setiap file yang membutuhkan model tersebut.
3. Variabel plan digunakan untuk mempresentasikan data atau objek yang akan ditampilkan dalam tamplilan PlanScreen. pendeklarasian plan sebagai konstanta digunakan agar objek plan yang dibuat tidak dapat diubah setelah dimulai. ni berguna dalam situasi di mana objek plan hanya perlu dibaca dan tidak dapat diubah, sehingga mengurangi risiko perubahan tak terduga pada data plan.
4. -
5. Fungsi method dalam langkah 11-13
   fungsi method initState() yaitu method yang digunakan untuk menginisiasi ScrollController dan menambha listener untuk merespon perubahan posisi scroll.
   menambah controller dan behavior pada ListView digunakan untuk menghubungkan Scroll ke ListView dan mengatur  perilaku keyboard saat melakukan Scrolling.
   fungsi method dispose digunakan untuk membersihkan resource ketika widget tidak digunakan lagi atau akan dihapus. ScrollController. dispose digunakan untuk membersihkan ScrollController saat widget dihapus, dengan tujuan melindungi memori dari kebocoran yang dapat terjadi jika controller tidak dibuang setelah digunakan
