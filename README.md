# Membuat aplikasi Multi Vendor Ecommerce dengan menggunakan Django Framework
[Github repositori](https://github.com/gurnitha/django_multivendor_ecom)


## [1. Setup](https://github.com/gurnitha/django_multivendor_ecom/commit/59e4443e7d97395ebc78be569d5493f222950a71)


#### [1.1 Modifikasi README.md file](https://github.com/gurnitha/django_multivendor_ecom/commit/ca8cd05ac6aa2f8d9d626559046e8d931684ffe4)

        Aktivitas:

        1. Modifikasi README.md file

        modified:   README.md


#### [1.2 Modifikasi links](https://github.com/gurnitha/django_multivendor_ecom/commit/4e1bdd18a700dd3b54ae428610a12141e92d0703)

        Aktivitas:

        1. Modifikasi links

        modified:   README.md


## [2. Membuat Proyek dan App](https://github.com/gurnitha/django_multivendor_ecom/commit/6f170234b2c4226936cb317ea74ac3f1ddb7c43d)

        Aktivitas:

        1. Membuat sub judul

        modified:   README.md


#### [2.1 Menginstal django](https://github.com/gurnitha/django_multivendor_ecom/commit/5b4973fe3152f182f000edde38e5980d7922ac1a)

        Aktivitas:

        1. Membuat virtual environment
        >  python -m venv venv3932
        2. Mengaktifkan venv3932
        >  venv3932\Scripts\activate
        2. Menginstal django v3.2
        >  pip install django==3.2
        3. Modifikasi .gitignore file

        modified:   .gitignore
        modified:   README.md


#### 2.2 Membuat django proyek dengan nama 'config'

        Aktivitas:

        1. Membuat proyek
        >  django-admin startproject config .
        2. Testing: djalankan django server
        >  python manage.py runserver
        3. Buka browser
        >  http://127.0.0.1:8000/

        Hasil testing: berhasil 

        modified:   README.md
        new file:   config/__init__.py
        new file:   config/asgi.py
        new file:   config/settings.py
        new file:   config/urls.py
        new file:   config/wsgi.py
        new file:   manage.py