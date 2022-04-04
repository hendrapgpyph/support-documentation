Handler
=======

:Qualified name: ``App\Exceptions\Handler``

.. php:class:: Handler

  .. php:method:: public render ($request, Exception $exception)

    Render an exception into an HTTP response.

    :param $request:
    :param Exception $exception:
    :returns: \Illuminate\Http\Response

  .. php:method:: public report (Exception $exception)

    Report or log an exception.

    :param Exception $exception:
    :returns: void

