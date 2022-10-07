# SIG_Peta-populasi-Bukittinggi

1. Download file ne_10m_populated_places_simple.zip pada browser QGIS. Lalu pilih file ne_10m_populated_places_simple.shp dan seret ke kanvas (*Gambar 1).

2. Pada file ne_10m_populated_places_simple.shp kita dapat melihat titik yang mewakili tempat-tempat berpenduduk. Tampilan default di kanvas QGIS menunjukkan geometri lapisan GIS. Pada setiap titik memiliki atribut (*Gambar 2).

3. Pada bilah alat atribut berisi banyak alat yang berguna untuk memeriksa, melihat, memilih, dan memodifikasi atribut. Klik tombol identify features. Setelah itu klik titik mana pun di kanvas (*Gambar 3, *Gambar 4).

4. Kita dapat melihat atribut semuanya bersama-sama pada sebuah tabel. Klik Open atribute table pada attributes toolbar. Atau dapat juga dengan mengklik kanan layer ne_10m_populated_places_simple dan pilih OPen Attrinute Table (*Gambar 5).

5. Akan tambil tabel dari atribut. Kita dapat menggulir secara horizontal dan menemukan kolom pop_max. Ini berisi populasi tempat terkait (*Gambar 6).

6. Selanjutnya kita bisa melakukan query pada atribut-atribut ini. QGIS menggunakan ekspresi seperti SQL untuk melakukan query. Klik select features using an expression (*Gambar 7).

7. Pada Select By Expression, klik bagian fields and values lalu klik dua kali pada label pop_max. Kita akan melihat bahwa itu ditambahkan ke bagian ekspresi di bagian bawah. Sebagai contoh disini kita mencari fitur yang memiliki populasi lebih dari 506963. Setelah itu klik Select Features lalu close (*Gambar 8).

8. Kita akan melihat bahwa beberapa baris dalam tabel atribut sekaran. Pada tabel ini akan menunjukkan jumlag fitur yang dipilih (*Gambar 9).

9. Tutup jendela atribut dan kembali pada jendela utama QGIS. Kita akan melihat bahwa subset poin sekarang dirender dengan warna kuning. Ini merupakan hasuil dari query dan poin yang dipilih yang memiliki pop_max lebih besar 506963 (*Gambar 10).

10. Untuk menyertakan syarat bahwa tempat itu juga menjadi ibu kota selain memiliki populasi lebih dari 506963. Kita dapat membuka editor ekspresi dengan menggunakan tombol Select Features by Expression pada attibutes toolbar (*Gambar 11).

11. Pada kolom yang berisi data tentang huruf kapital adalah adm0cap. Nilai 1 menunjukkan bahwa tempat tersebut ibukota. Kita dapat menambahkan kriterian ini ke ekspresi sebelumnya. Masukkan ekspresi sesuai pada gambar setelah itu klik Select Features lalu close (*Gambar 12).

12. Sekarang kita akan mengeskpor fitur yang dipilih sebagai layer baru. Klik kanan pada layer ne_10m_populated_places simple dan klik eksport + Save Selected Features As.. (*Gambar 13).

13. Kita dapat memilih format apa pun yang kita suka sebagai format. Untuk ini kita memilih GeoJSON. GeoJSON adalah format berbasis teks yang digunakan secara luas dalam pemetaan web. Klik tombol di sebelah nama file dan masukkan nama peta sebagai file output (*Gambar 14).

14. data input memiliki banyak kolom. Kita dapat meilih sebagian dari kolom asli untu, di export. Pilih bidang yang akan di export. Klik Deselect All dan centang kolom name dan pop_max lalu klik OK (*Gambar 15).

15. Selanjutnya kita dapat melihat hasilnya seperti pada gambar (*Gambar 16).

