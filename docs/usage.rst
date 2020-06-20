=====
Usage
=====

To use Simple Phone Number Field in a project, add it to your `INSTALLED_APPS`:

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
