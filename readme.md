## Catatan Penting untuk Pemeriksaan Project

Yth. Bapak Fahry, M.Kom,

Terima kasih telah memeriksa repositori project saya. 

Sebelum menjalankan program, mohon izin untuk menginformasikan bahwa konfigurasi (*database*) pada repositori ini disesuaikan dengan lingkungan *localhost* perangkat saya. Oleh karena itu, agar program dapat berjalan dengan normal di perangkat Bapak, mohon bantuan untuk menyesuaikan konfigurasi pada file berikut:

**`application/config/database.php`**

Beberapa baris yang kemungkinan perlu disesuaikan dengan pengaturan di perangkat Bapak meliputi:

```php
$db['default'] = array(
    'dsn'   => '',
    'hostname' => 'localhost',
    'username' => 'username_database',
    'password' => 'password_database', 
    'database' => 'nama_database',
    // ...
);