# Belajar Vi dan Vim
Vi merupakan teks editor default yang ada pada sistem operasi berbasis UNIX. Sedangkan Vim merupakan teks editor tiruan Vi, namun telah ditingkatkan sehingga memiliki banyak fitur daripada Vi.

## Membuat dan Masuk ke dalam File
```
vi <nama_file>
```
```
vim <nama_file>
```
- contoh
```
vi index.html
```
```
vim index.html
```

## Menyimpan Kegiatan (Melakukan Save)
```
:w!
```

## Keluar Vi/Vim Tanpa Menyimpan Kegiatan
```
:q!
```

## Keluar Vi/Vim Dengan Menyimpan Kegiatan
```
:wq!
```

## Memindahkan Kursor
- Memindahkan Kursor ke bawah
```
tekan j
```
- Memindahkan Kursor ke atas
```
tekan k
```
- Memindahkan Kursor ke kanan
```
tekan l
```
- Memindahkan Kursor ke atas
```
tekan h
```
- Memindahkan Kursor ke colom paling atas/pertama
```
tekan gg
```
- Memindahkan Kursor ke colom paling bawah/terakhir
```
tekan G (Huruf Kapital)
```
- Memindahkan Kursor ke baris paling kiri
```
tekan 0 (nol)
```
- Memindahkan Kursor ke baris paling kanan
```
tekan $ (Dollar)
```

## Insert Text
- Insert text ke kiri
```
tekan i
```
- Insert text ke kanan
```
tekan a
```
- Insert text ke kolom selanjutnya
```
tekan o
```
- Insert text ke kolom sebelumnya
```
tekan O (Huruf Kapital)
```

## Delete Text
- Delete text satu baris
```
tekan dd
```
- Delete text, satu kata ke kanan
```
tekan dw
```
- Delete text, satu kata ke kiri
```
tekan db
```
- Delete text, semua baris
```
tekan dG
```

## Copy Text
- Copy text satu baris
```
tekan yy
```

## Cut Text
- Cut text satu baris
```
tekan dd
```
- Cut text, satu kata ke kanan
```
tekan dw
```
- Cut text, satu kata ke kiri
```
tekan db
```
- Cut text, semua baris
```
tekan dG
```

## Paste Text
- Paste text kebawah kolom
```
tekan p
```
- Paste text keatas kolom
```
tekan P (Huruf Kapital)
```

## Find Text
```
tekan /
```
contoh pencarian
```
tekan /html
```
setelah itu tekan n (kecil) untuk mencari kalimat atau text ke bawah.
lalu tekan N (besar) untuk mencari kalimat atau text ke atas.

# Catatan

### Set Number
Set number digunakan untuk menampilkan angka pada setiap baris di code editor Vi dan Vim
```
:set number
```

### Syntax On
Syntax on digunakan untuk menghighlight code pada Vi dan Vim.
```
:syntax on
```
