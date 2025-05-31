
🛒 Autocomplete Pencarian Produk E-Commerce dengan Trie
Proyek ini merupakan simulasi fitur pencarian otomatis (autocomplete) pada platform e-commerce. Tujuan utamanya adalah meningkatkan efisiensi pencarian produk dengan memberikan saran otomatis yang relevan saat pengguna mulai mengetik.

Fitur ini dibangun dengan struktur data Trie, yang akan melakukan pencarian  berdasarkan awalan (prefix) dengan cepat dan efisien, bahkan dalam jumlah data produk yang besar.

🔍 Apa Proyek Ini Sebenarnya?
Proyek ini bertujuan untuk membuat ulang fitur autocomplete serupa seperti di Tokopedia, Shopee, dan e-commerce lainnya, tetapi dengan menggunakan struktur data Trie, bukan database tradisional atau metode pencarian biasa.

Saat pengguna mengetik awalan produk, sistem akan menampilkan daftar nama produk yang relevan secara real-time, berdasarkan data yang tersimpan dalam Trie. Seluruh proses ini dilakukan di dalam notebook Python.

🧩 Penjelasan Per Bagian Kode
1. Membaca Data Produk
Data nama produk dibaca dari file Excel atau CSV menggunakan pandas.

2. Pembersihan Teks (Clean Text)
Data dibersihkan: dikonversi ke huruf kecil, dibuang karakter tidak penting, dan disaring agar tidak duplikat.

3. Pembuatan Struktur Trie
Struktur Trie dan TrieNode dibuat untuk menyusun karakter dari nama produk menjadi pohon awalan.

4. Memasukkan Data ke dalam Trie
Nama produk dimasukkan satu per satu ke dalam Trie agar siap digunakan untuk pencarian awalan.

5. Visualisasi Trie
Struktur Trie divisualisasikan menggunakan graphviz, dibatasi hingga 40 node dan kedalaman 4 level agar mudah dibaca.

6. Menampilkan Produk Relevan Berdasarkan Input Pengguna
Pengguna memasukkan awalan kata, dan sistem langsung menampilkan daftar produk relevan yang cocok dengan awalan tersebut — seperti fitur pencarian otomatis pada e-commerce.

✅ Langkah yang Harus Dilakukan Pengguna
Siapkan file data_produk saya gunakan sebagai dataset produk (.csv atau .xlsx).
Jalankan TREE CLOUDE.ipynb di Jupyter Notebook / Google Colab.
Ikuti langkah-langkah mulai dari membaca file, pembersihan teks, membentuk Trie, hingga mencoba fitur autocomplete.
Masukkan awalan nama produk dan lihat hasil saran produk yang relevan.


