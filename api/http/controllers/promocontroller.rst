PromoController
===============

:Qualified name: ``App\Http\Controllers\PromoController``
:Extends: :class:`Controller`

.. php:class:: PromoController

  .. php:method:: public __construct ()


  .. php:method:: public create ()

    Menampilkan formulir promo.

    :returns: \Illuminate\Http\Response

  .. php:method:: public deleteCheckedPromo (Request $request)

    Proses menghapus data promo yang di check

    :param Request $request:
    :returns: json

  .. php:method:: public deleteData ($id)

    Proses menghapus data promo

    :param $id:
    :returns: json

  .. php:method:: public destroy ($id)

    Proses menghapus data promo (not used).

    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public edit ($id)

    Menampilkan formulir edit promo.

    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public getPromoData (Request $request)

    Mengambil data promo dalam bentuk json

    :param Request $request:
    :returns: json

  .. php:method:: public getPromoEdit ($id)

    Menampilkan data promo yang di edit

    :param $id:
    :returns: json

  .. php:method:: public index ()

    Menampilkan halaman promo.

    :returns: \Illuminate\Http\Response

  .. php:method:: public publikasi (Request $request)

    Proses untuk publikasi data promo

    :param Request $request:
    :returns: json

  .. php:method:: public show (Promo $promo)

    Display the specified resource.

    :param Promo $promo:
    :returns: \Illuminate\Http\Response

  .. php:method:: public store (Request $request)

    Proses untuk menambahkan data promo.

    :param Request $request:
    :returns: \Illuminate\Http\Response

  .. php:method:: public update (Request $request, $id)

    Proses update data promo.

    :param Request $request:
    :param $id:
    :returns: \Illuminate\Http\Response

