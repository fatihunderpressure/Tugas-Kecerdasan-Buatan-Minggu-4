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

## Deskripsi Tugas 3
Mengubah *Semantic Network* (Jaringan Semantik) menjadi bentuk *Frame*. *Frame* adalah struktur data yang digunakan untuk merepresentasikan pengetahuan dalam bentuk tabel yang terdiri dari **Slot** (Atribut) dan **Filler** (Nilai/Isi).

## Penjelasan Frame (Tugas 3)
Berdasarkan diagram *Semantic Network Example*, berikut adalah representasi *Frame*-nya:

## Deskripsi Tugas 3
Mengubah *Semantic Network* (Jaringan Semantik) menjadi bentuk *Frame*. *Frame* adalah struktur data untuk merepresentasikan pengetahuan dalam bentuk tabel (**Slot** dan **Filler**).

## Penjelasan Frame Berdasarkan Diagram
Berikut adalah detail *Frame* yang diekstrak dari *Semantic Network Example*:

1. **Frame: Bird**
   - **ISA**: Animal
   - **Has-part**: Wing, Tail, Feather
   - **Eats**: Seeds
   - **Can**: Fly

2. **Frame: Penguin**
   - **ISA**: Bird
   - **Cannot**: Fly
   - **Instances**: Opus

3. **Frame: Opus**
   - **INST**: Penguin

4. **Frame: Canary**
   - **ISA**: Bird, Pet
   - **Instances**: Tweety

5. **Frame: Tweety**
   - **INST**: Canary

6. **Frame: Mammal**
   - **ISA**: Animal
   - **Has-part**: Tail
   - **Subclasses**: Cat, Dog

7. **Frame: Cat**
   - **ISA**: Mammal
   - **Eats**: Cat Food
   - **Instances**: Garfield, Sylvester

8. **Frame: Garfield**
   - **INST**: Cat
   - **Eats**: Lasagna
