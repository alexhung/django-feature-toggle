==============
Feature Toggle
==============

Feature Toggle is a simple Django app based on the behavioural pattern `Feature Toggle <https://martinfowler.com/articles/feature-toggles.html>`_ proposed by Martin Fowler.

Quick links
===========
    PyPi: `https://pypi.org/project/django-feature-toggle/ <https://pypi.org/project/django-feature-toggle/>`_


    Source: `https://github.com/thulasi-ram/django-feature-toggle <https://github.com/thulasi-ram/django-feature-toggle>`_


    Docs: `https://thulasi-ram.github.io/django-feature-toggle <https://thulasi-ram.github.io/django-feature-toggle>`_



Quickstart
==========
1. Install the package ``pip install django-feature-toggle``

2. Add "feature_toggle" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'feature_toggle',
    ]

3. Run ``python manage.py migrate`` to create the models required feature_toggle.

4. Start your app to use the feature_toggle.