=============================
django-forum
=============================

.. image:: https://badge.fury.io/py/django-forum.svg
    :target: https://badge.fury.io/py/django-forum

.. image:: https://requires.io/github/exolever/django-forum/requirements.svg?branch=master
     :target: https://requires.io/github/exolever/django-forum/requirements/?branch=master
     :alt: Requirements Status

.. image:: https://travis-ci.org/exolever/django-forum.svg?branch=master
    :target: https://travis-ci.org/exolever/django-forum

.. image:: https://codecov.io/gh/exolever/django-forum/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/exolever/django-forum

.. image:: https://sonarcloud.io/api/project_badges/measure?project=exolever_django-forums&metric=alert_status
   :target: https://sonarcloud.io/dashboard?id=exolever_django-forum
   
.. image:: https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat
   :target: https://github.com/exolever/django-forum/issues
   
.. image:: https://img.shields.io/badge/License-MIT-green.svg
   :target: https://opensource.org/licenses/MIT

Implement forum for Django


Quickstart
----------

Install django-forum::

    pip install django-forum

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'forum',
        ...
    )

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
