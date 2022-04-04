NewsController
==============

:Qualified name: ``App\Http\Controllers\Api\NewsController``
:Extends: :class:`Controller`

.. php:class:: NewsController

  .. php:method:: public all ()

    Fungsi untuk mendapatkan seluruh news diurutkan berdasarkan tanggal rilis news

    :returns: void

  .. php:method:: public detailNews (Request $request)

    Fungsi untuk mendapatkan detail news

    :param Request $request:
    :returns: void

  .. php:method:: public index ()

    Fungsi untuk mendapatkan list news secara random maksimal 4 news

    :returns: void

  .. php:method:: public newsLainnya (Request $request)

    Fungsi untuk mendapatkan data news lainnya

    :param Request $request:
    :returns: void

  .. php:method:: public searchNews (Request $request)

    Fungsi untuk mencari news

    :param Request $request:
    :returns: void

