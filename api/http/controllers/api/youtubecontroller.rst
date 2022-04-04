YoutubeController
=================

:Qualified name: ``App\Http\Controllers\Api\YoutubeController``
:Extends: :class:`Controller`

.. php:class:: YoutubeController

  .. php:method:: public getApi ($key)

    Fungsi untuk melakukan fetch ke API youtube

    :param $key:
    :returns: void

  .. php:method:: public getDetail ($key, $id)

    Fungsi untuk melakukan fetch ke API youtube untuk mendapatkan detail video yang di cari

    :param $key:
    :param $id:
    :returns: void

  .. php:method:: public getDetailVideoYoutube (Request $req)

    Fungsi untuk mendapatkan detail dari video youtube yang di cari

    :param Request $req:
    :returns: void

  .. php:method:: public getYoutube (Request $request)

    Fungsi untuk mendapatkan video Youtube Jinom diurutkan dari video terbaru

    :param Request $request:
    :returns: void

