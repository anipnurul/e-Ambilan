## INSTALASI
---
###langkah 1

git clone https://github.com/mutaqim96/e-ambilan-dynamic-menu.git

###langkah 2
jalankan perintah ``composer install``

###langkah 3
tukar nama file **.env.example** kepada **.env**

###langkah 4
* jalankan perintah ``php artisan key:generate`` untuk generate ``App Key``

ubahsuai isi kandungan **.env**
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=e-ambilan
DB_USERNAME=root
DB_PASSWORD=
```

###langkah 5
cipta database dengan nama **e-ambilan**

###langkah 6
jalankan perintah ``php artisan migrate``

###langkah 7
jalankan perintah ``php artisan migrate --seed``



