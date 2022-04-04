NewsController
==============

:Qualified name: ``App\Http\Controllers\NewsController``
:Extends: :class:`Controller`

.. php:class:: NewsController

  .. php:method:: public __construct ()


  .. php:method:: public create ()

    Menampilkan halaman form news.

    :returns: \Illuminate\Http\Response

  .. php:method:: public deleteCheckedNews (Request $request)

    Menghapus data news yang dipilih

    :param Request $request:
    :returns: void

  .. php:method:: public deleteData ($id)

    Proses untuk menghapus data news

    :param $id:
    :returns: void

  .. php:method:: public destroy ($id)

    Proses untuk menghapus data news. (not used)

    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public edit ($id)

    Menampilkan formulir edit news.

    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public getNewsData (Request $request)

    Mendapatkan data news diurutkan berdasarkan tanggal publish terbaru

    :param Request $request:
    :returns: void

  .. php:method:: public getNewsEdit ($id)

    Menampilkan data news yang di edit

    :param $id:
    :returns: void

  .. php:method:: public index ()

    Menampilkan halaman news.

    :returns: \Illuminate\Http\Response

  .. php:method:: public publikasi (Request $request)

    Proses publikasi news yang dipilih

    :param Request $request:
    :returns: void

  .. php:method:: public show (News $news)

    Display the specified resource.

    :param News $news:
    :returns: \Illuminate\Http\Response

  .. php:method:: public store (Request $request)

    Proses untuk menambahkan data news.

    :param Request $request:
    :returns: \Illuminate\Http\Response

  .. php:method:: public update (Request $request, $id)

    Proses untuk mengupdate data news.

    :param Request $request:
    :param $id:
    :returns: \Illuminate\Http\Response

