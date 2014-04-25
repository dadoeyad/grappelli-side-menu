=============================
grappelli-side-menu
=============================

.. image:: https://badge.fury.io/py/grappelli-side-menu.png
    :target: https://badge.fury.io/py/grappelli-side-menu

.. image:: https://travis-ci.org/dadoeyad/grappelli-side-menu.png?branch=master
    :target: https://travis-ci.org/dadoeyad/grappelli-side-menu

.. image:: https://coveralls.io/repos/dadoeyad/grappelli-side-menu/badge.png?branch=master
    :target: https://coveralls.io/r/dadoeyad/grappelli-side-menu?branch=master

Side menu for Grappelli, the Django admin Interface


Quickstart
----------

Install grappelli-side-menu::

    pip install grappelli-side-menu

Add "grappelli_menu" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = (
        'grappelli_menu',
        'grappelli',
        'django.contrib.admin',
        .....
    )

Add `django.core.context_processors.request` to your TEMPLATE_CONTEXT_PROCESSORS if it's not there already::

    TEMPLATE_CONTEXT_PROCESSORS = (
        .....
        "django.core.context_processors.request",
    )

Features
--------

* TODO