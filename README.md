# Tugas-Kecerdasan-Buatan-Minggu-4

# Tugas Kecerdasan Buatan - Jaringan Semantik

## Deskripsi Tugas 2
Memperluas jaringan semantik dasar (Ayam -> Unggas) dengan menambahkan objek yang setingkat, lebih khusus, dan lebih umum.

## Penjelasan Diagram (Tugas 2.png)
Berdasarkan diagram yang telah saya buat, berikut adalah detail perluasannya:

1. **Objek yang Sama (Sibling):** - **Bebek**: Ditambahkan sebagai objek yang setingkat dengan *Ayam*. Keduanya merupakan jenis *Unggas*.
   
2. **Objek yang Lebih Khusus (Specific):** - **Ayam Jago**: Merupakan spesialisasi atau jenis kelamin tertentu dari *Ayam*. Relasinya: "Ayam Jago adalah Ayam".

3. **Objek yang Lebih Umum (General):** - **Hewan**: Merupakan kategori puncak. *Unggas* adalah bagian dari kategori *Hewan*.

## Struktur Hubungan
- **Ayam Jago** -> (adalah) -> **Ayam**
- **Ayam & Bebek** -> (adalah) -> **Unggas**
- **Unggas** -> (adalah) -> **Hewan**
- **Unggas** -> (memiliki) -> **Sayap**
- **Unggas** -> (makan) -> **Biji-bijian**
