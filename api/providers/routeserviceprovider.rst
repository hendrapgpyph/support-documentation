RouteServiceProvider
====================

:Qualified name: ``App\Providers\RouteServiceProvider``

.. php:class:: RouteServiceProvider

  .. php:method:: public boot ()

    Define your route model bindings, pattern filters, etc.

    :returns: void

  .. php:method:: public map ()

    Define the routes for the application.

    :returns: void

  .. php:method:: protected mapApiRoutes ()

    Define the "api" routes for the application.
These routes are typically stateless.

    :returns: void

  .. php:method:: protected mapWebRoutes ()

    Define the "web" routes for the application.
These routes all receive session state, CSRF protection, etc.

    :returns: void

