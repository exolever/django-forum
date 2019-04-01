=====
Usage
=====

To use forum in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'forum',
        ...
    )

Add forum's URL patterns:

.. code-block:: python

    from forum import urls


    urlpatterns = [
        ...
        url(r'^', include(forum.urls)),
        ...
    ]
