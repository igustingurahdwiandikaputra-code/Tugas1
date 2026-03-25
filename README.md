# Tugas1
# 1. Penjelasan konsep array

Array (python berupa list) adalah struktur data yang digunakan untuk menyimpan banyak nilai dalam satu variabel.

Contoh array di Python
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/FOTO%201.png?raw=true)

a. nilai_mahasiswa = []
Membuat array kosong untuk menampung nilai mahasiswa.
b. for i in range(10):
Perulangan sebanyak 10 kali, artinya program akan meminta input 10 nilai.
c. angka = int(input("Masukkan angka: "))
Mengambil input dari user, lalu mengubahnya menjadi tipe integer (angka).
d. nilai_mahasiswa.append(angka)
Menambahkan setiap nilai yang diinput ke dalam array nilai_mahasiswa.

Intinya, array berfungsi sebagai wadah untuk menyimpan 10 nilai mahasiswa yang diinput satu per satu, lalu dikumpulkan dalam satu variabel agar bisa diproses lebih lanjut untuk digunakan dalam mencari  nilai tertinggi, nilai terendah, dan rata-rata.

# 2. Screenshot hasil eksekusi

# CODE 1 (INPUT NILAI)
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/FOTO%201.png?raw=true)
# CODE 2 (MENGHITUNG NILAI MAX, MIN, SUM)
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/FOTO%202.png?raw=true)
# CODE 3 (HITUNG KELULUSAN)
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/FOTO%203.png?raw=true)
# CODE 4 (HASIL HITUNGAN)
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/FOTO%204.png?raw=true)
# CODE 5 (GRAFIK NILAI)
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/FOTO%205.png?raw=true)
# CODE 6 (GRAFIK LULUS)
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/FOTO%206.png?raw=true)
# HASIL 1 
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/HASIL%201.png?raw=true)
# HASIL 2
![alt text](https://github.com/igustingurahdwiandikaputra-code/Tugas1/blob/main/HASIL%202.png?raw=true)

# 3. Analisis kompleksitas

Program ini memproses data nilai mahasiswa yang disimpan dalam array dengan jumlah data sebanyak n.

# A. INPUT NILAI 10 MAHASISWA O(n)
Program menerima input sejumlah data yang dimasukkan, sehingga bergantung pada banyaknya data.
# B. MENGHITUNG NILAI TERTINGGI, TERENDAH, RATA-RATA O(n)
Seluruh elemen dalam array harus diperiksa untuk menemukan nilai tertinggi dan terendah, dan Semua nilai dijumlahkan terlebih dahulu sebelum dibagi dengan jumlah data.
# C. MENGHITUNG LULUS O(n)
Setiap data diperiksa satu per satu untuk menentukan apakah memenuhi kriteria lulus >=60 

Karena sebagian besar proses mengharuskan penelusuran seluruh data, kompleksitas total program termasuk dalam O(n).
Artinya, semakin banyak data yang diolah, maka waktu yang dibutuhkan program juga akan meningkat secara sebanding.


# 4. Refleksi pembelajaran

Melalui tugas ini, saya belajar memanfaatkan struktur data array pada Python untuk menampung dan mengelola kumpulan data. Saya juga menguasai operasi dasar seperti menentukan nilai maksimum, minimum, menghitung rata-rata, serta melakukan seleksi data untuk menentukan mahasiswa yang lulus berdasarkan kriteria tertentu.

Di sisi lain, saya memahami konsep kompleksitas algoritma, di mana proses yang melibatkan penelusuran seluruh data memiliki kompleksitas O(n), sedangkan proses seperti pembuatan grafik lebih sederhana karena hanya menggunakan data yang sudah tersedia. Library Matplotlib juga sangat membantu dalam menyajikan data dalam bentuk visual.

Secara umum, proyek ini memberikan pemahaman tentang hubungan antara pengolahan data, efisiensi algoritma, dan penyajian informasi, sehingga program yang dibuat tidak hanya mampu mengolah data dengan baik tetapi juga menampilkan hasil secara lebih jelas dan informatif.

