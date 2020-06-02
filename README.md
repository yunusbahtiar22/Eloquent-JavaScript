# Mahir JavaScript

Ini adalah sumber yang digunakan untuk menyusun edisi ketiga Mahir
Javascript  (https://mahirjavascript.net).

Kami menyambut masukan dalam bentuk issue dan pull request. 

## Cara Menyusun

Perintah ini menyusun keluaran HTML di direktori `html/`, sedangkan 
`make` adalah perintah make dari GNU:

    npm install
    make html

Untuk menyusun berkas PDF (anda tidak perlu melakukan hal ini kecuali 
anda sangat memerlukannya, karena daftar ini akan kadaluarsa dan prosesnya
sangatlah sulit):

    apt-get install texlive texlive-xetex fonts-inconsolata fonts-symbola texlive-lang-chinese inkscape
    make book.pdf

## Penerjemahan

Kami sangat menyambut pihak yang ingin menerjemahkan naskah ini. Lisensi
buku ini mengizinkan turunan tak komersial, termasuk terjemahan terbuka.
Jika anda memiliki rencana untuk melakukannya, mohon kabari saya, sehingga
saya bisa menambahkan tautan ke situs.

Tetapi, saya ingin memperingatkan: tulisan ini terdiri dari 130000
kata, sementara buku kertasnya terdiri dari 400 halaman. Teks yang
cukup banyak dan membutuhkan waktu yang lama untuk diterjemahkan.

Jika peringatan itu tidak membuat anda takut, cara terbaik untuk
memulai terjemahan adalah:

- Cabangkan repositori ini di Github.
- Buat sebuah isu di repositori yang menjelaskan rencana anda
- Terjemahkan berkas dengan tipe `.md` di cabang anda. Gunakan format [CommonMark](https://commonmark.org), dengan beberapa penambahan. Anda mungkin bisa mengabaikan terma indeks (yang ditandai dengan tanda kurung ganda dan sintaks `{{index ...}}`) dari terjemahan anda, karena itu hanya relevan untuk keluaran cetak.
- Publikasikan secara daring atau minta saya untuk menampungnya.

Jika anda melakukan ini di publik, dan membuat isu yang bertaut dengan pekerjaan anda, akan membantu mencegah kerja ganda, dimana beberapa orang memulai terjemahan dalam bahasa yang sama (dan mungkin tidak menyelesaikannya). (Karena terjemahan harus mempertahankan lisensinya, anda boleh mengambil terjemahan orang lain dan meneruskan usahanya, bahkan jika sumber aslinya sudah tidak ada di internet.)
