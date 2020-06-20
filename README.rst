=============================
Simple Phone Number Field
=============================

.. image:: https://badge.fury.io/py/drf-phone-number-field.svg
    :target: https://badge.fury.io/py/drf-phone-number-field

.. image:: https://travis-ci.org/tusharsarang/drf-phone-number-field.svg?branch=master
    :target: https://travis-ci.org/tusharsarang/drf-phone-number-field

.. image:: https://codecov.io/gh/tusharsarang/drf-phone-number-field/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/tusharsarang/drf-phone-number-field

Provide Django Model Field for PhoneNumber

Documentation
-------------

The full documentation is at https://drf-phone-number-field.readthedocs.io.

Quickstart
----------

Install Simple Phone Number Field::

    pip install drf-phone-number-field

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'drf_phone_number_field.apps.DrfPhoneNumberFieldConfig',
        ...
    )

Add Simple Phone Number Field's URL patterns:

.. code-block:: python

    from drf_phone_number_field import urls as drf_phone_number_field_urls


    urlpatterns = [
        ...
        url(r'^', include(drf_phone_number_field_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
