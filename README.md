# Deskripsi Singkat
Halo, ini merupakan repositori untuk mata kuliah Komputasi Paralel 2022. Beberapa konten yang akan ada seperti Catatan Perkuliahan, Tugas, Kuis, dan banyak hal lainnya. 

# Tim
**Kelompok Intel - Komputasi Paralel 2022**
- 120450024, M. Alfin Delvan Joeyantu
- 120450034, M. Zaky Mahdavikia Zein
- 120450034, Muhammad Dafha Syahrizal
- 120450081, Dimas Wahyu Saputro

# Cara untuk Kontribusi
## Kontribusi Pertama

Sulit. Selalu sulit saat pertama kali Anda melakukan sesuatu. Terutama ketika Anda berkolaborasi, membuat kesalahan bukanlah hal yang nyaman. Membaca artikel dan menonton tutorial dapat membantu, tetapi apa yang lebih baik daripada langsung mempraktikan hal-hal tersebut? Jika Anda ingin memberikan kontribusi untuk pertama kalinya, ikuti langkah-langkah di bawah ini.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

Apabila belum memiliki git, [ install segera ](https://help.github.com/articles/set-up-git/).

## Fork Repositori Ini

Fork repositori ini dengan cara menekan tombol *fork* yang ada di bagian kanan atas layar.
Hal tersebut akan membuat salinan repositori ini di akun anda.

## Klon Repositori

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Sekarang klon repositori ini ke komputer anda. Tekan tombol *clone* lalu tekan ikon "copy to clipboard".

Buka terminal dan eksekusi perintah git berikut:

```
git clone "url yang telah Anda salin"
```

yang mana "url yang telah Anda salin" (tanpa tanda petik) adalah url ke repositori ini. Lihat langkah sebelumnya untuk mendapatkan url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

Contoh:

```
git clone https://github.com/username-anda/parallel-computing
```

`username-anda` adalah *username* Github Anda. Pada langkah ini, Anda menyalin konten dari repositori first-contributions di GitHub ke komputer anda.

## Membuat Cabang (Branch)

Pindah ke direktori repositori Anda yang baru saja disalin (jika belum ada di sana):

```
cd parallel-computing
```

Buat cabang dengan perintah `git checkout`:

```
git checkout -b <add-nama-cabang-baru>
```

Contoh:

```
git checkout -b add-dimas-new
```

(Nama cabang tidak perlu mengandung kata _add_ namun layak untuk ditambahkan karena tujuan dari cabang ini adalah menambahkan nama Anda ke dalam sebuah daftar.)

## Buat Perubahan yang Diperlukan Lalu Commit Perubahan Tersebut

Buat dan kerjakan bagian tugas anda. Apabila Anda masuk ke direktori dan mengeksekusi perintah `git status` maka Anda dapat melihat bahwa telah ada perubahan. Tambahkan perubahan tersebut ke dalam cabang yang sebelumnya telah dibuat menggunakan perintah `git add`:

```
git add Contributors.md
```

Simpan perubahan tersebut menggunakan perintah `git commit`:

```
git commit -m "Add <nama> to Contributors list"
```

Ubah `<nama>` dengan nama anda.

## Dorong (Push) Perubahan ke GitHub

Dorong perubahan menggunakan perintah `git push`:

```
git push origin <add-nama-cabang-baru>
```

Ubah `<add-nama-cabang-baru>` dengan nama cabang yang sebelumnya telah dibuat.

## Submit Perubahan untuk Diperiksa

Jika Anda membuka repositori Anda di GitHub, maka akan ada tombol `Compare & pull request`. Tekan tombol tersebut.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Kirimkan *Pull Request* (PR)

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Segera Saya (pengelola) akan menggabungkan semua perubahan Anda ke cabang utama dari proyek ini. Anda akan mendapatkan email notifikasi setelah perubahan digabungkan.

## Ke Mana Lagi Setelah dari Sini?

Selamat! Anda baru saja menyelesaikan *fork* -> *clone* -> ubah -> *Pull Request* sebuah alur kerja yang akan sering Anda temui sebagai kontributor!