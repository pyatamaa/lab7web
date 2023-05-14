# konfigurasi untuk penggunaan codeigniter 4

---

1. download codeigniter4 yang bisa didownload pada codeigniter.com

2. buat folder **lab11_ci** pada htdocs lalu masukkan file codeigniter yang sudah di ekstrak

3. rename folder codeigniter yang awalnya **codeigniter4-framework-v4....** menjadi **ci4**

4. pada folder ci4 cari file bernama **env** kemudian rename menjadi **.env**

5. buka file .env kemudian ubah **CI_ENVIRONMENT = production** menjadi **CI_ENVIRONMENT = development** kemudian save

# konfigurasi xampp untuk mengakses codeigniter 4

---

1. buka xampp lalu pilih config pada apache kemudian pilih php.ini

![Screenshot (126)](https://github.com/Pyatamaa/lab7web/assets/92738041/7f198849-31ab-40ea-8b37-57f258de57f1)

2. cari **;extension=intl** kemudian hapus tanda titik koma

![Screenshot (127)](https://github.com/Pyatamaa/lab7web/assets/92738041/354aaa17-ccaf-443c-bddf-8908e5d7fe5b)

3. nyalakan apache dan buka shell pada xampp kemudian masuk ke directory ci4 yang terdapat didalam folder lab11_ci dalam htdocs xampp. Setelah itu coba tes dengan mengetik **php spark**

![Screenshot (122)](https://github.com/Pyatamaa/lab7web/assets/92738041/dae14e87-7b53-46cf-b89d-915bb5032f04)

apabila muncul output seperti dibawah ini, maka lanjutkan dengan mengetik **php spark serve** untuk mengakses codeigniter kita

![Screenshot (123)](https://github.com/Pyatamaa/lab7web/assets/92738041/6644ce77-8393-4310-b848-8ba8e226a094)

4. setelah itu akan muncul code seperti ini yang bisa kita gunakan untuk mengakses codeigniter kita

![Screenshot (125)](https://github.com/Pyatamaa/lab7web/assets/92738041/bc236c8b-06d7-489f-9bd3-60377ef97eb1)

#output

![Screenshot (121)](https://github.com/Pyatamaa/lab7web/assets/92738041/2766ba54-326d-42e0-8031-42ac00937c05)
