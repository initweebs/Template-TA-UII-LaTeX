


Quick Start
-----------
1. Siapkan LaTeX environment pada komputer anda, begitu pula LaTeX editornya. File yang diperlukan biasanya berukuran besar, jadi siapkan koneksi internet yang lancar jaya.
	- [*Windows*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8)
	- [*Linux*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=linux+setup+latex)
	- [*Mac OS X*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=mac+setup+latex)
	- [Editor LaTeX di web](https://www.overleaf.com/) bisa dengan overleaf.com. Dengan ini kita tidak usah repot siapkan LaTeX environment.



Contents
--------
Berikut penjelasan dari file-file utama dalam template ini. File lain yang tidak tercantum hanya pelengkap dalam repository ini.

		template-skripsi/
			├── gambar/
			│	   ├── logougm.png
			│	   └── wsn.png
			├── bab1.tex
			├── bab2.tex
			├── bab3.tex
			├── bab4.tex
			├── bab5.tex
			├── daftar-pustaka.bib
			├── template-skripsi.pdf
			├── template-skripsi.tex
			└── jtetiskripsi.cls

### bab1.tex - bab5.tex
Konten utama dari skripsi, mulai dari BAB I (pendahuluan) sampe BAB V (kesimpulan). Silakan disesuaikan dengan jumlah bab skripsi anda, hapus file yang tidak perlu atau tambahkan file baru untuk bab baru.

### daftar-pustaka.bib
File yang berisi daftar referensi-referensi yang anda gunakan dalam skripsi. File ini penting guna menyusun daftar pustaka anda. Dengan file ini menyusun daftar pustaka menjadi sangat sangat sangat mudah.

File ini adalah hasil export dari aplikasi *reference management* seperti Mendeley, Zotero, EndNote, dll. Biasakan mengorganisir referensi skripsi anda menggunakan aplikasi *reference management*.

### template-skripsi.tex
File ini template-skripsi.tex adalah file utama (kepala) dari template. Berisi informasi-informasi dasar, seperti judul skripsi, nama penulis, nama pembimbing, dll.

### template-skripsi.pdf
File ini adalah skripsi anda dalam bentuk matang. Sudah rapi dan dapat dicetak untuk dijilid. File ini di-*generate* secara otomatis menggunakan LaTeX.

### jtetiskripsi.cls
File yang berisi aturan-aturan format skripsi. Contoh, format cover, halaman pengesahan, daftar isi, daftar pustaka, dan konten skripsi.

Jika anda ingin memodifikasi template skripsi ini, ubahlah file *jtetiskripsi.cls*.

### gambar/
Masukkan gambar-gambar pada skripsi anda di folder ini. Gambar default: logougm.png (dipakai di cover) dan wsn.png (hanya dipakai di template awal, silakan dihapus jika tidak diperlukan).
			
Bonus
-----
Jika anda *clone* repository ini dengan [Git](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=setup+git), anda akan temukan tiga branch:
	
	- master
	- perpus-pusat
	- skripsi-guntur

Branch master merupakan template skripsi, dengan isi yang sudah disesuaikan.

Namun branch perpus-pusat dan skripsi-guntur adalah skripsi saya :D. Silakan baca-baca, semoga bermanfaat. Perpus-pusat adalah skripsi dengan tambahan lembar pernyataan dan lembar pengesahan asli, guna dikumpulkan di Perpus Pusat UGM.

Lisensi
-------
Template sripsi ini dilisensikan dengan menggunakan [lisensi MIT](https://raw.githubusercontent.com/gtrdp/template-skripsi/master/LICENSE).
