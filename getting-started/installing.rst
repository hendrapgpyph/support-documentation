Installation
============

System Requirements
-------------------

.. note::

    Berikut system requirement yang diperlukan untuk menginstall website HomeNet

Website memiliki beberapa dependensi pada paket perangkat lunak lain. Pastikan Anda memiliki ini
tersedia sebelum menginstal aplikasi website HomeNet.

-  `PHP 7.4.0`_ or higher
-  Composer_

Installing Website HomeNet
------------------------

Clone aplikasi website HomeNet dengan menjalankan command berikut ::

   $ git clone https://gitlab.com/jinomdev/homenet.id.git

Selesai clone project jalankan composer install dengan menjalankan command berikut ::

   $ composer install

Kemudian jalankan composer dump-autoload untuk load semua class yang ada ::

   $ composer dump-autoload

Proses Instalasi Selesai

Selanjutnya
--------

Setelah melakukan instalasi, selanjutnya melakukan proses konfigurasi :doc:`configuration`.

.. _XSD: https://github.com/phpDocumentor/phpDocumentor/blob/master/data/xsd/phpdoc.xsd
.. _Docker image:           https://hub.docker.com/r/phpdoc/phpdoc
.. _Composer:               https://getcomposer.org
.. _`PHP 7.4.0`:            https://www.php.net
.. _Graphviz:               https://graphviz.org/download/
.. _PlantUML:               https://plantuml.com/download
.. _Twig:                   https://twig.symfony.com/
.. _Phive website:          https://phar.io/
.. _phive:                  https://phar.io/
