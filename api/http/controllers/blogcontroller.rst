BlogController
==============

:Qualified name: ``App\Http\Controllers\BlogController``
:Extends: :class:`Controller`

.. php:class:: BlogController

  .. php:method:: public TestNewBlog (Request $req)

    Test new function aja deh

    :param Request $req:

  .. php:method:: public __construct ()


  .. php:method:: public create ()

    Menampilkan halaman form blog.

    :returns: \Illuminate\Http\Response

  .. php:method:: public deleteCheckedBlog (Request $request)

    Fungsi untuk menghapus blog yang di check

    :param Request $request:
    :returns: void

  .. php:method:: public deleteData ($id)

    Fungsi untuk menghapus data blog serta slider terkait

    :param $id:
    :returns: void

  .. php:method:: public destroy ($id)

    Fungsi untuk menghapus data blog.

    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public edit ($id)

    Menampilkan halaman edit blog

    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public getBlogData (Request $request)

    Get data blog dalam bentuk json

    :param Request $request:
    :returns: void

  .. php:method:: public index ()

    Menampilkan halaman Blog

    :returns: \Illuminate\Http\Response

  .. php:method:: public publikasi (Request $request)

    Fungsi untuk set publikasi blog yang dipilih

    :param Request $request:
    :returns: void

  .. php:method:: public show (Blog $blog)

    Fungsi untuk menampilkan list blog.

    :param Blog $blog:
    :returns: \Illuminate\Http\Response

  .. php:method:: public store (Request $request)

    Fungsi untuk menyimpan data blog.

    :param Request $request:
    :returns: \Illuminate\Http\Response

  .. php:method:: public update (Request $request, $id)

    Fungsi untuk proses update data blog

    :param Request $request:
    :param $id:
    :returns: \Illuminate\Http\Response

