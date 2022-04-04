RegisterController
==================

:Qualified name: ``App\Http\Controllers\Auth\RegisterController``
:Extends: :class:`Controller`

.. php:class:: RegisterController

  .. php:method:: public __construct ()

    Create a new controller instance.

    :returns: void

  .. php:method:: protected create (array $data)

    Create a new user instance after a valid registration.

    :param array $data:
    :returns: \App\User

  .. php:method:: protected validator (array $data)

    Get a validator for an incoming registration request.

    :param array $data:
    :returns: \Illuminate\Contracts\Validation\Validator

