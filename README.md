# Program Persegi Panjang (Python OOP)

Program sederhana berbasis Python yang mengimplementasikan konsep *Object-Oriented Programming* (OOP) untuk menghitung keliling dan luas persegi panjang.

---

## Penjelasan Kode

### 1. File `persegi_panjang.py`
File ini berisi definisi kelas `PersegiPanjang` beserta method-method didalamnya:

* **`__init__(self, panjang, lebar)`**: Konstruktor yang berfungsi untuk menginisialisasi atribut `panjang` dan `lebar` saat objek pertama kali dibuat.
* **`keliling(self)`**: Method untuk menghitung keliling persegi panjang dengan rumus `2 * (panjang + lebar)`.
* **`luas(self)`**: Method untuk menghitung luas persegi panjang dengan rumus `panjang * lebar`.
* **`__str__(self)`**: Method khusus (*dunder method*) untuk mengembalikan representasi string dari objek secara otomatis saat dipanggil oleh fungsi `print()`.

### 2. File `main.py`
File ini berfungsi sebagai alur utama eksekusi program:

1. Mengimpor kelas `PersegiPanjang` dari file `persegi_panjang.py`.
2. Membuat objek `pp` dengan nilai `panjang = 3` dan `lebar = 2`.
3. Mencek informasi objek melalui fungsi `print(pp)`.
4. Mengakses method `keliling()` dan `luas()` untuk menampilkan hasil perhitungannya.

---

## Output Program

```text
persegi panjang, panjang 3 cm, dan lebar 2 cm
Keliling: 10 cm
Luas: 6 cm²
