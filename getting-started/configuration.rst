Configuration
=============

Konfigurasi Awal
-------------------

Konfigurasi website HomeNet dapat dilakukan dengan memasukkan command yang disediakan pada dokumentasi command dibawah ini

Copy env example dengan command sebagai berikut ::

   $ cp .env.example .env

Jalankan artisan key generate ::

   $ php artisan key:generate

Lakukan clear cache ::

   $ php artisan config:cache

Jalankan Migrasi database dengan menjalankan command berikut ::

   $ php artisan migrate

Production & Debug
-------------------

.. note::

    Production Mode merupakan mode aplikasi berjalan secara real dalam proses bisnis yang berjalan pada aplikasi.
    Debug Mode merupakan mode aplikasi berjalan secara tidak real / sedang testing dalam proses bisnis yang berjalan pada aplikasi

Perlu diketahui untuk menjalankan website dengan mode production atau debug hanya perlu mengubah config yang ada pada file .env
pada bagian APP_DEBUG = true (Debugging Mode) atau APP_DEBUG = false (Production Mode)

.. code-block:: xml

    APP_NAME="HomeNet"
    APP_ENV=local
    APP_KEY={app_key}
    APP_DEBUG=true
    APP_URL=http://localhost
.. _XSD: https://github.com/phpDocumentor/phpDocumentor/blob/master/data/xsd/phpdoc.xsd
