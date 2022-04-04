UserController
==============

:Qualified name: ``App\Http\Controllers\UserController``
:Extends: :class:`Controller`

.. php:class:: UserController

  .. php:method:: public __construct ()


  .. php:method:: public deleteCheckedUser (Request $request)

    Proses menghapus user yang dipilih

    :param Request $request:
    :returns: json

  .. php:method:: public delete_user (Request $request)

    Proses menghapus user

    :param Request $request:
    :returns: json

  .. php:method:: public edit_user (Request $request, $id)

    Menampilkan halaman edit user

    :param Request $request:
    :param $id:
    :returns: view

  .. php:method:: public form_user ()

    Menampilkan halaman user

    :returns: view

  .. php:method:: public getUserData (Request $request)

    Menampilkan data user

    :param Request $request:
    :returns: json

  .. php:method:: public profil (Request $request, $id)

    Menampilkan halaman profile user

    :param Request $request:
    :param $id:
    :returns: view

  .. php:method:: public store_user (Request $request)

    Proses tambah user

    :param Request $request:
    :returns: json

  .. php:method:: public update_profil (Request $request, $id)

    Proses update data profile

    :param Request $request:
    :param $id:
    :returns: json

  .. php:method:: public user ()

    Menampilkan halaman user

    :returns: void

