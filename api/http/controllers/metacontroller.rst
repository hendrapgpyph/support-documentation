MetaController
==============

:Qualified name: ``App\Http\Controllers\MetaController``
:Extends: :class:`Controller`

.. php:class:: MetaController

  .. php:method:: public all ()

    Menampilkan halaman serta menyertakan data meta

    :returns: void

  .. php:method:: public apiBlogDetail ($id)

    Mendapatkan meta blog dengan format json

    :param $id:
    :returns: void

  .. php:method:: public blogDetail ($id)

    Menampilkan halaman dengan meta sesuai dengan blog yang dipilih

    :param $id:
    :returns: void

  .. php:method:: public newsDetail ($id)

    Menampilkan halaman dengan meta sesuai dengan news yang dipilih

    :param $id:
    :returns: void

  .. php:method:: public promoDetail ($id)

    Menampilkan halaman dengan meta sesuai dengan promo yang dipilih

    :param $id:
    :returns: void

  .. php:method:: public testReverse ()

    API untuk test reverse wilayah json

    :returns: void

