=====
Usage
=====

To use forum in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'forum.apps.ForumConfig',
        ...
    )

Add forum's URL patterns:

.. code-block:: python

    from forum import urls as forum_urls


    urlpatterns = [
        ...
        url(r'^', include(forum_urls)),
        ...
    ]
