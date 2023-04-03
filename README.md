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


#### [2.2 Membuat django proyek dengan nama 'config'](https://github.com/gurnitha/django_multivendor_ecom/commit/36b9086d122df9088b7bfb77b886d8208fcfe934)

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


#### [2.3 Membuat django app](https://github.com/gurnitha/django_multivendor_ecom/commit/ec4af8e6cdd8c4d0e3f9376686ce334ca67c25ed)

        Aktivitas:

        1. Membuat direktori
        >  mkdir app\core
        2. Membuat django app dengan nama 'core'
        >  python manage.py startapp core app\core

        modified:   README.md
        new file:   app/core/__init__.py
        new file:   app/core/admin.py
        new file:   app/core/apps.py
        new file:   app/core/migrations/__init__.py
        new file:   app/core/models.py
        new file:   app/core/tests.py
        new file:   app/core/views.


#### [2.4 Register django app pada proyek](https://github.com/gurnitha/django_multivendor_ecom/commit/cbc92441807fd91263e3ed8cefdd8c90bc5ca5a3)

        Aktivitas:

        1. Modifikasi app name
        modified:   app/core/apps.py
        2. Register django app
        modified:   config/settings.py
        3. Modifikasi README.md file
        modified:   README.md
        4. Testing: 


## 3. Django Urls, Views, Templates

        Aktivitas:

        1. modified:   README.md


#### [3.1 Hello Wordl menggunakan url, view and templates](https://github.com/gurnitha/django_multivendor_ecom/commit/c6c6d5efae26d27a7bd3312417885fd7940f2144)

        Aktivitas:

        1. new file:   app/core/urls.py
        2. modified:   app/core/views.py
        3. modified:   config/settings.py
        4. modified:   config/urls.py
        5. new file:   templates/app/core/index.html
        6. modified:   README.md

        Testing: :)


#### [3.2 Mengisi html template untuk index.html](https://github.com/gurnitha/django_multivendor_ecom/commit/128f35f0db551e81ec1d5aa82dfe22492b22a755)

        Aktivitas:

        1. modified:   templates/app/core/index.html
        2. modified:   README.md


## 4. Static dan Media files

        Aktivitas:

        1. modified:   README.md


#### [4.1 Setting up path dan root static dan media files](https://github.com/gurnitha/django_multivendor_ecom/commit/854545765400f5c7a71a057bd408f3e870864579)

        Aktivitas:

        1. modified:   config/settings.py
        2. modified:   config/urls.py
        3. modified:   .gitignore
        4. modified:   README.md


#### 4.2 Add dan loading static files

        Aktivitas:

        1. modified:   templates/app/core/index.html
        2. modified:   README.md

        Testing dan hasilnya :)
