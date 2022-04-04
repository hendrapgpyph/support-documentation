BlogController
==============

:Qualified name: ``App\Http\Controllers\Api\BlogController``
:Extends: :class:`Controller`

.. php:class:: BlogController

  .. php:method:: public all (Request $request)

    Fungsi untuk mendapatkan seluruh list blog

    :param Request $request:
    :returns: void

  .. php:method:: public blogTerkait (Request $request)

    Fungsi untuk mendapatkan data dari Blog Terkait

    :param Request $request:
    :returns: void

  .. php:method:: public data_blog (Request $request)

    Fungsi untuk mendapatkan data Blog

    :param Request $request:
    :returns: void

  .. php:method:: public data_blog_lainnya (Request $request)

    Fungsi untuk mendapatkan data blog lainnya

    :param Request $request:
    :returns: void

  .. php:method:: public detailBlogKategoris (Request $request)

    Fungsi untuk mendapatkan kategori pada detail blog

    :param Request $request:
    :returns: void

  .. php:method:: public detailBlogs (Request $request)

    Fungsi untuk mendapatkan detail blog

    :param Request $request:
    :returns: void

  .. php:method:: public detailJSONBlogs (Request $request)

    Fungsi untuk mendapatkan detail blog berbentuk JSON

    :param Request $request:
    :returns: void

  .. php:method:: public index ()

    Fungsi untuk mendapatkan list blog secara random

    :returns: void

  .. php:method:: public kategoriBlog (Request $request)

    Fungsi untuk get data kategori Blog

    :param Request $request:
    :returns: void

  .. php:method:: public populer ()

    Fungsi untuk mendapatkan data blog populer

    :returns: void

  .. php:method:: public searchBlog (Request $request)

    Fungsi untuk mencari blog

    :param Request $request:
    :returns: void

  .. php:method:: public searchBlogKategori (Request $request)

    Fungsi untuk mencari blog dengan kategori

    :param Request $request:
    :returns: void

