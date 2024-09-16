
# Project Analisis Sentimen
## ScrapReviewRiliv_App.ipynb
## Deskripsi

Proyek ini menggunakan analisis sentimen untuk bahasa Inggris. Jika Anda ingin mengubah analisis sentimen ke bahasa Indonesia, harap ikuti petunjuk di bawah ini.
Jika anda ingin mengubah sentimen ke indonesia Harap ubah bagian :
1. Take Data :
ubah bagian lang menjadi "id" agar yang diambil Indonesia
2. Remove Emoji and Stopword :
ubah bagian stopword dari "english" ke Indonesia

## Instalasi

Sebelum menjalankan proyek ini di lingkungan lokal Anda, pastikan untuk menginstal semua dependensi yang diperlukan atau perhatikan module yang di instal di dalam kode ipynb agar semuanya berjalan dengan baik. Gunakan perintah berikut untuk menginstal requirements:

```bash
pip install -r requirements.txt

# Beberapa Interpretasi Kalimat yang mungkin ambigu dalam DATA Riliv : Mental Health App

## "Aplikasinya ringan"

1. **Aplikasi tersebut memiliki beban atau ukuran file yang kecil.**
   - **ringan** - Adjektif yang menggambarkan ukuran atau beban.

2. **Aplikasi tersebut tidak menyebabkan perangkat menjadi lambat atau berat.**
   - **ringan** - Adjektif yang menggambarkan performa aplikasi.

3. **Penggunaan aplikasi tersebut tidak memerlukan banyak sumber daya dari sistem.**
   - **ringan** - Adjektif yang menggambarkan kebutuhan sumber daya atau konsumsi memori.

4. **Aplikasi tersebut mudah digunakan dan tidak rumit.**
   - **ringan** - Adjektif yang menggambarkan kemudahan penggunaan.

5. **Aplikasi tersebut tidak memerlukan waktu lama untuk diunduh atau diinstal.**
   - **ringan** - Adjektif yang menggambarkan waktu unduh atau instalasi.

- **ringan** - Secara morfologis dan sintaksis, ambigu: dapat berarti ukuran, performa, kemudahan penggunaan, atau waktu unduh/install.
- **Aplikasinya** - Sintaksis ambigu: merujuk pada aplikasi yang dimaksud atau kualitas aplikasi tersebut.
- **ringan** - Secara semantik ambigu: bisa merujuk pada ukuran, performa, kemudahan, atau efisiensi waktu.

## "Udah nyaman padahal tapi tiba-tiba gak bisa login"

1. **Pengguna merasa sudah nyaman dengan aplikasi atau layanan tersebut, tetapi tiba-tiba tidak bisa masuk ke dalamnya.**
   - **nyaman** - Adjektif yang menggambarkan kepuasan atau kenyamanan pengguna terhadap aplikasi atau layanan.
   - **login** - Verba yang menggambarkan proses masuk ke dalam sistem yang mengalami masalah.

2. **Pengguna sudah merasa puas dengan aplikasi atau layanan sebelumnya, namun kini mengalami masalah saat mencoba login.**
   - **nyaman** - Adjektif yang menunjukkan kepuasan atau kenyamanan yang dirasakan sebelumnya.
   - **login** - Verba yang menunjukkan proses akses yang tidak berhasil.

3. **Setelah merasa nyaman menggunakan aplikasi, pengguna mendapati masalah login yang muncul secara tiba-tiba.**
   - **nyaman** - Adjektif yang menggambarkan keadaan yang diharapkan atau telah terbiasa.
   - **login** - Verba yang merujuk pada gangguan yang baru terjadi.

4. **Pengguna telah terbiasa dengan kenyamanan aplikasi, tetapi kini tidak dapat mengakses aplikasi tersebut karena masalah login yang tidak terduga.**
   - **nyaman** - Adjektif yang menunjukkan kondisi sebelum masalah muncul.
   - **login** - Verba yang menggambarkan masalah akses.

5. **Meskipun aplikasi sebelumnya nyaman digunakan, pengguna mengalami kendala tiba-tiba dalam proses login.**
   - **nyaman** - Adjektif yang menggambarkan kepuasan atau kenyamanan yang sudah dirasakan.
   - **login** - Verba yang menggambarkan kendala yang terjadi secara tiba-tiba.

- **nyaman** - Secara morfologis dan sintaksis, ambigu: dapat berarti kepuasan, ketidaknyamanan, atau kenyamanan secara umum.
- **login** - Secara semantik ambigu: bisa merujuk pada berbagai jenis masalah akses.
- **tiba-tiba** - Secara semantik ambigu: bisa merujuk pada kejadian yang tidak terduga.
- **Udah** - Secara sintaksis, bisa berarti sudah atau merasa sudah dalam konteks informal.

## "Aku baru coba semoga jadi my secret book"

1. **Aku baru saja mencoba sesuatu, dan berharap itu akan menjadi buku rahasiaku.**
   - **baru** - Adverbia yang menunjukkan bahwa tindakan mencoba baru saja dilakukan.
   - **coba** - Verba yang menggambarkan tindakan percobaan.
   - **my secret book** - Noun phrase yang merujuk pada buku yang ingin menjadi rahasia.

2. **Aku baru mulai mencoba ide atau proyek ini, dan berharap hasilnya bisa menjadi buku rahasiaku.**
   - **baru** - Adverbia yang menunjukkan tahap awal dari percobaan atau proses.
   - **coba** - Verba yang merujuk pada upaya awal atau eksperimen.
   - **my secret book** - Noun phrase yang menunjukkan buku yang diharapkan menjadi rahasia.

3. **Aku baru mencoba metode atau cara ini dan berharap itu akan menjadikan hasilnya sebagai buku rahasiaku.**
   - **baru** - Adverbia yang mengindikasikan bahwa metode atau cara tersebut baru dicoba.
   - **coba** - Verba yang merujuk pada upaya baru dalam metode atau cara tertentu.
   - **my secret book** - Noun phrase yang menunjukkan hasil akhir yang diinginkan.

4. **Aku baru mencoba menulis atau menciptakan sesuatu, dan berharap itu akan menjadi buku rahasiaku.**
   - **baru** - Adverbia yang menunjukkan bahwa aktivitas menulis atau menciptakan baru saja dimulai.
   - **coba** - Verba yang menggambarkan proses mencoba menulis atau menciptakan.
   - **my secret book** - Noun phrase yang merujuk pada karya yang ingin dirahasiakan.

5. **Aku baru mencoba ide untuk sebuah buku dan berharap buku tersebut akan menjadi rahasiaku.**
   - **baru** - Adverbia yang menunjukkan tahap awal dari percobaan ide.
   - **coba** - Verba yang menggambarkan percobaan ide atau konsep.
   - **my secret book** - Noun phrase yang diharapkan menjadi buku rahasia.

- **baru** - Secara morfologis dan sintaksis, ambigu: bisa merujuk pada waktu percobaan yang baru atau tahap awal.
- **coba** - Secara semantik ambigu: bisa merujuk pada percobaan, eksperimen, atau upaya.
- **my secret book** - Secara sintaksis ambigu: bisa berarti buku yang menjadi rahasia penulis atau buku yang diharapkan akan menjadi rahasia.
- **my secret book** - Secara semantik ambigu: bisa merujuk pada buku yang dirahasiakan oleh penulis atau buku yang diharapkan memiliki kualitas khusus.

## "Membantu menenangkan"

1. **Memberikan dukungan atau bantuan untuk membuat seseorang merasa lebih tenang.**
   - **membantu** - Verba yang menggambarkan tindakan memberikan bantuan atau dukungan.
   - **menenangkan** - Verba yang menggambarkan proses membuat seseorang merasa tenang.

2. **Menggunakan metode atau teknik tertentu untuk menenangkan suasana atau situasi.**
   - **membantu** - Verba yang merujuk pada tindakan melakukan sesuatu untuk tujuan tertentu.
   - **menenangkan** - Verba yang menggambarkan upaya mengurangi ketegangan atau stres.

3. **Memberikan saran atau nasihat yang dapat membuat seseorang merasa lebih tenang.**
   - **membantu** - Verba yang menggambarkan tindakan memberikan saran atau nasihat.
   - **menenangkan** - Verba yang menggambarkan efek dari saran atau nasihat tersebut dalam membuat seseorang merasa tenang.

4. **Menggunakan produk atau aktivitas yang dapat membantu dalam proses menenangkan diri.**
   - **membantu** - Verba yang menggambarkan penggunaan produk atau aktivitas untuk efek tertentu.
   - **menenangkan** - Verba yang merujuk pada proses mencapai keadaan tenang.

5. **Memberikan bantuan dalam bentuk metode relaksasi untuk mengurangi stres atau kecemasan.**
   - **membantu** - Verba yang menggambarkan tindakan memberikan bantuan dalam bentuk metode relaksasi.
   - **menenangkan** - Verba yang menggambarkan efek dari metode relaksasi dalam mengurangi stres atau kecemasan.

- **membantu** - Secara morfologis dan sintaksis, ambigu: bisa berarti memberikan dukungan, saran, atau produk.
- **menenangkan** - Secara semantik ambigu: bisa merujuk pada proses membuat seseorang tenang, mengurangi stres, atau menenangkan suasana.
- **menenangkan** - Secara sintaksis dan semantik, ambigu: bisa berarti efek dari bantuan dalam membuat seseorang tenang, suasana lebih tenang, atau mengurangi kecemasan.
