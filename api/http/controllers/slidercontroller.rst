SliderController
================

:Qualified name: ``App\Http\Controllers\SliderController``
:Extends: :class:`Controller`

.. php:class:: SliderController

  .. php:method:: public __construct ()


  .. php:method:: public addData (Request $request, $id)

    Proses menambahkan data slider

    :param Request $request:
    :param $id:
    :returns: json

  .. php:method:: public create ()

    Show the form for creating a new resource.

    :returns: \Illuminate\Http\Response

  .. php:method:: public deleteData ($id)

    Proses menghapus data slider

    :param $id:
    :returns: json

  .. php:method:: public destroy (Slider $slider)

    Remove the specified resource from storage.

    :param Slider $slider:
    :returns: \Illuminate\Http\Response

  .. php:method:: public edit (Slider $slider)

    Show the form for editing the specified resource.

    :param Slider $slider:
    :returns: \Illuminate\Http\Response

  .. php:method:: public getBlogSlider (Request $request)

    Mendapatkan data slider blog

    :param Request $request:
    :returns: json

  .. php:method:: public getNewsSlider (Request $request)

    Mendapatkan data news slider

    :param Request $request:
    :returns: json

  .. php:method:: public getPromoSlider (Request $request)

    Mendapatkan data slider promo

    :param Request $request:
    :returns: json

  .. php:method:: public getSliderData (Request $request)

    Mendapatkan data slider

    :param Request $request:
    :returns: json

  .. php:method:: public index ()

    Display a listing of the resource.

    :returns: \Illuminate\Http\Response

  .. php:method:: public publikasi (Request $request)

    Proses untuk publikasi data slider

    :param Request $request:
    :returns: json

  .. php:method:: public show (Slider $slider)

    Display the specified resource.

    :param Slider $slider:
    :returns: \Illuminate\Http\Response

  .. php:method:: public store (Request $request, $id)

    Store a newly created resource in storage.

    :param Request $request:
    :param $id:
    :returns: \Illuminate\Http\Response

  .. php:method:: public update (Request $request, Slider $slider)

    Update the specified resource in storage.

    :param Request $request:
    :param Slider $slider:
    :returns: \Illuminate\Http\Response

