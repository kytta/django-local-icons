django-local-icons
==================

|latest-version| |python-support| |django-support|

.. |latest-version| image:: https://img.shields.io/pypi/v/django-local-icons.svg
   :target: https://pypi.org/project/django-local-icons/
   :alt: Latest version on PyPI

.. |python-support| image:: https://img.shields.io/pypi/pyversions/django-local-icons
   :target: https://pypi.org/project/django-local-icons/
   :alt: Supported Python versions

.. |django-support| image:: https://img.shields.io/pypi/djversions/django-local-icons
   :target: https://pypi.org/project/django-local-icons/
   :alt: Supported Django versions

django-local-icons makes working with icons for your websites way easier.

It provides useful template tags for including SVG- and Webfont-based icons,
either from local files or from the web. And with a handy manage script, you
can download icons from Iconify framework for self-hosting.

Install
-------

1. Install django-local-icons as you would install a Python package, i.e. with
pip, pipenv, Poetry, etc.

2. Include ``local_icons`` in your ``INSTALLED_APPS``::

    INSTALLED_APPS = [
        ...,  # other apps
        'local_icons',
    ]

3. Load the icons with a template tag::

    {% load local_icons %}

    {# This will include '/static/icons/person_outline.svg' #}
    {% icon 'person_outline' %}

4. Check out the docs at https://django-local-icons.readthedocs.io/

Contribute
----------

- **Issue tracker:** https://codeberg.org/kytta/django-local-icons/issues

Licence
-------

| Copyright © 2022, `Nikita Karamov`_
| Licensed under the `BSD 3-Clause "New" or "Revised" License`_

.. _Nikita Karamov: https://www.kytta.dev/
.. _BSD 3-Clause "New" or "Revised" License: https://spdx.org/licenses/BSD-3-Clause.html

----

This project is hosted on Codeberg: https://codeberg.org/kytta/django-local-icons
