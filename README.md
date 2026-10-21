# CRUD Auth (+ Session Cookie) Example Laravel

Repository ini digunakan untuk praktikum Laravel pert 8 & 9.

## Persyaratan

- PHP min 8.3.30
- Laravel 13
- Composer
- MySQL (pastikan Laragon/MySQL sudah nyala!)
- Git

## Instalasi

1. Clone repository:

   ```bash
   git clone [URL_REPOSITORY]
   cd crud-session-cookie-test
   ```

2. Instal dependency:

   ```bash
   composer install
   ```

3. Salin `.env.example` menjadi `.env`. dengan cara ketik di terminal
    ```bash
    cp .env.example .env
    ```

4. Buat database MySQL kosong dengan nama *dbexample_praktikum* (pastikan kosong, jika sudah ada hapus dan bikin ulang)

5. Buat application key:

   ```bash
   php artisan key:generate
   ```

6. Atur konfigurasi database pada `.env`.

7. Buat tabel dan data contoh:

   ```bash
   php artisan migrate --seed
   ```

8. Jalankan aplikasi:

   ```bash
   php artisan serve
   ```

9. Buka `http://127.0.0.1:8000`.

## Data Contoh

Seeder menyediakan data pelanggan dan satu akun pengguna untuk kebutuhan latihan.

## Catatan

- Jangan mengunggah file `.env` ke repository.
- Setiap praktikan menggunakan database lokal masing-masing.
- Jangan menghapus atau mereset database yang berisi data penting.
