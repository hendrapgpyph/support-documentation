KategoriController
==================

:Qualified name: ``App\Http\Controllers\KategoriController``
:Extends: :class:`Controller`

.. php:class:: KategoriController

  .. php:method:: public __construct ()


  .. php:method:: public create ()

    Show the form for creating a new resource.

    :returns: \Illuminate\Http\Response

  .. php:method:: public deleteCheckedKategori (Request $request)

    Proses menghapus data kategori yang dipilih

    :param Request $request:
    :returns: void

  .. php:method:: public deleteData ($id)

    Proses menghapus data kategori

    :param $id:
    :returns: void

  .. php:method:: public destroy ($id)

    Proses menghapus data kategori (not used).

    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public edit ($id)

    Menampilkan data kategori untuk di edit.

    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public getKategoriData (Request $request)

    Mendapatkan data kategori

    :param Request $request:
    :returns: void

  .. php:method:: public index ()

    Menampilkan halaman kategori.

    :returns: \Illuminate\Http\Response

  .. php:method:: public publikasi (Request $request)

    Proses untuk publikasi kategori

    :param Request $request:
    :returns: void

  .. php:method:: public show (Kategori $kategori)

    Store a newly created resource in storage.

    :param Kategori $kategori:
    :returns: \Illuminate\Http\Response Display the specified resource.

  .. php:method:: public store (Request $request)

    Menyimpan data kategori

    :param Request $request:
    :returns: void

  .. php:method:: public update (Request $request, $id)

    Proses update data kategori.

    :param Request $request:
    :param $id:
    :returns: \Illuminate\Http\Response

