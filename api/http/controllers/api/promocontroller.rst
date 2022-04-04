PromoController
===============

:Qualified name: ``App\Http\Controllers\Api\PromoController``
:Extends: :class:`Controller`

.. php:class:: PromoController

  .. php:method:: public PromoWilayah (Request $req)

    Fungsi untuk mendapatkan wilayah yang sedang promo

    :param Request $req:
    :returns: void

  .. php:method:: public all ()

    Fungsi untuk mendapatkan seluruh data promo diurutkan berdasarkan tanggal rilis terbaru

    :returns: void

  .. php:method:: public detailPromos (Request $request)

    Fungsi untuk mendapatkan detail promo

    :param Request $request:
    :returns: void

  .. php:method:: public index ()

    Fungsi untuk mendapatkan list promo secara random maksimal 4 promo

    :returns: void

  .. php:method:: public promoLainnya (Request $request)

    Fungsi untuk mendapatkan data promo lainnya

    :param Request $request:
    :returns: void

  .. php:method:: public searchPromo (Request $request)

    Fungsi untuk mencari promo

    :param Request $request:
    :returns: void

