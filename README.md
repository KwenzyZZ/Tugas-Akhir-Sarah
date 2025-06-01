Berikut README.md yang sudah aku sesuaikan dengan nama file dan repo yang kamu berikan:

---

````markdown
# Program Daftar Nilai Mahasiswa

Program sederhana berbasis C++ untuk memasukkan data nilai mahasiswa dan menentukan status kelulusan berdasarkan nilai yang diinput.

---

## Deskripsi Program

Program ini memungkinkan pengguna untuk memasukkan data sejumlah mahasiswa, termasuk nama dan nilai mereka.  
Kemudian program akan menentukan status kelulusan mahasiswa berdasarkan kriteria berikut:

- Nilai **≤ 70** → Status: **Tidak Lulus**
- Nilai **> 70** → Status: **Lulus**

Setelah semua data dimasukkan, program akan menampilkan daftar nilai lengkap dengan status masing-masing mahasiswa.

---

## Cara Menjalankan

### 1. Clone repository

```bash
git clone https://github.com/KwenzyZZ/Tugas-Akhir-Sarah.git
cd Tugas-Akhir-Sarah
````

### 2. Compile program

Gunakan compiler C++ (misal `g++`):

```bash
g++ tugas-akhir.cpp -o daftar_nilai
```

### 3. Jalankan program

```bash
./daftar_nilai     # Linux/macOS
daftar_nilai.exe   # Windows
```

### 4. Masukkan data sesuai perintah di layar

Program akan meminta jumlah data mahasiswa, lalu masukkan nama dan nilai satu per satu.

---

## Contoh Input & Output

```
Masukkan Jumlah Data = 2

Data ke-1
Masukkan Nama = Andi
Masukkan Nilai = 85

Data ke-2
Masukkan Nama = Budi
Masukkan Nilai = 65

DAFTAR NILAI MAHASISWA
------------------------------------------------------------------------------------
No		Nama			Nilai				Status   
------------------------------------------------------------------------------------
1		Andi			85				Lulus
------------------------------------------------------------------------------------
2		Budi			65				Tidak Lulus
------------------------------------------------------------------------------------
```



## Catatan

* Program menggunakan header `<conio.h>` untuk fungsi `getch()` yang biasanya tersedia di Windows.
  Jika kamu menggunakan Linux/macOS, kamu bisa menghapus `#include <conio.h>` dan `getch();` di akhir program.

