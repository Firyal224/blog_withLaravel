<h1 align="center">Blog simple</h1>








## User

**Admin**

- email: admin@gmail.com
- Password: admin123

**Penulis**

- email: writer@gmail.com
- Password: writer123

**Pembaca**

- email: pembaca@gmail.com
- Password: 123123123




## Buka di kode editor


## Install composer

```bash
composer install
```

## Copy .Env

```bash
copy .env.example menjadi .env
```

## Buat database di localhost 

```bash
nama database : laravel8_blog
```

## Setting database di .env

```bash
DB_PORT=3306
DB_DATABASE=laravel8_blog
DB_USERNAME=root
DB_PASSWORD=
```

## Generate key

```bash
php artisan key:generate
```

## Jalankan migrate dan seeder

```bash
php artisan migrate --seed
```

## Buat storage link

```bash
php artisan storage:link
```


