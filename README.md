**Submission Bookshelf API untuk Kelas Belajar Membuat Aplikasi Back-End untuk Pemula dari Dicoding Indonesia**

Kriteria Utama:
1. Aplikasi menggunakan port 9000.
2. Aplikasi dijalankan dengan perintah npm run start.
3. API dapat menyimpan buku melalui route POST /books.
4. API dapat menampilkan seluruh buku melalui route GET /books.
5. API dapat menampilkan detail buku melalui route GET /books/{bookId}.
6. API dapat mengubah data buku melalui route PUT /books/{bookId}.
7. API dapat menghapus buku melalui route DELETE /books/{bookId}.

Kriteria Tambahan pada Route GET /books:
1. Menampilkan seluruh buku yang mengandung nama berdasarkan nilai yang diberikan pada query /books?name=”{bookName}”.
2. Menampilkan buku yang sedang dibaca atau tidak melalui query /books?reading=0 atau /books?reading=1.
3. Menampilkan buku yang sudah selesai dibaca atau belum melalui query /books?finished=0 atau /books?finished=1.
