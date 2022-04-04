KontakController
================

:Qualified name: ``App\Http\Controllers\KontakController``
:Extends: :class:`Controller`

.. php:class:: KontakController

  .. php:method:: public __construct ()


  .. php:method:: public deleteCheckedKontak (Request $request)

    Menghapus data kontak yang dipilih

    :param Request $request:
    :returns: void

  .. php:method:: public deleteData ($id)

    Proses menghapus data kontak

    :param $id:
    :returns: void

  .. php:method:: public getKontakData (Request $request)

    Mendapatkan data kontak

    :param Request $request:
    :returns: void

  .. php:method:: public index ()

    Menampilkan halaman kontak

    :returns: void

  .. php:method:: public show (Kontak $kontak, $id)

    Menampilkan halaman kontak

    :param Kontak $kontak:
    :param $id:
    :returns: void

