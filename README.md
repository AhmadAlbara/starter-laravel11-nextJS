## Install
Cara Install Project ke local 
-   Follow Github Saya
-   Star Repo Github Saya
-   Fork Repo Github Saya
-   Clone project repo saya dengan cara menuliskan pada terminal/cmd/git bash :<br> <b>git clone</b>
``````
https://github.com/AhmadAlbara/starter-laravel11-nextJS.git
`````` 
-   lalu masuk ke direktori repo yg sudah di clone
-   masuk ke direktori server dan tulis pada terminal/cmd/git bash : <b>composser install </b>
- buat file .env dan copy kan semua yang terdapat pada file .env.example 
-   tulis migrate database pada terminal/cmd/git bash : 
``````
php artisan migrate
``````
- lalu jalan kan server nya dengan menggunakan perintah
``````
php artisan serve
``````
server akan berjalan pada http://localhost:8000

-  keluar dari direktori server dan  masuk ke direktori client setelah itu tulis pada terminal/cmd/git bash : <b>npm install </b>
- buat file .env.local dan copy kan semua yang terdapat pada file .env.example 

- lalu jalankan client side nya dengan perintah
``````
npm run dev
``````
client side akan berjalan pada http://localhost:3000
