# mahasiswa-php
Simpel restfull api menggunakan bahasa php

### Background
Projek ini untuk berbagi bagaimana membuat resfull api dengan bahasan php dan menggunakan framework codeigniter. Autentikasi untuk melakukan akses ke api telah diterapkan keamanan dengan token JWT. 

### Installation
Untuk menjalankan api ini membutuhkan konfigurasi file config.php dengan direktori application/config. Ganti konfig tersebut dengan url sistem yang akan anda gunakan. 

```sh
$config['base_url'] = 'http://localhost/mahasiswa-php/';
```
You might need to configure the database.php file as well if you have different settings for it.
```sh
$db['default'] = array(
	'dsn'	=> '',
	'hostname' => 'YOUR_HOST',
	'username' => 'YOUR_USERNAME',
	'password' => 'YOUR_PASSWORD',
	'database' => 'DATABASE_NAME',
	'dbdriver' => 'mysqli',
	'dbprefix' => '',
	'pconnect' => false,
	'db_debug' => (ENVIRONMENT !== 'production'),
	'cache_on' => false,
	'cachedir' => '',
	'char_set' => 'utf8',
	'dbcollat' => 'utf8_general_ci',
	'swap_pre' => '',
	'encrypt' => false,
	'compress' => false,
	'stricton' => false,
	'failover' => array(),
	'save_queries' => true
);
```
