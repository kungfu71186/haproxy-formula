=======
haproxy
=======

Install, configure and run ``haproxy``.

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================

.. contents::
    :local:

Use jinja template and the pillar for a salt approach. You can also use a flat file if you wish, although the template itself
is pretty generic in that it will parse whatever you put in. See pillar example.

``haproxy``
-----------

Install, configure and run ``haproxy`` service.

``haproxy.install``
-------------------

Install ``haproxy`` from packages.

``haproxy.config``
------------------


``haproxy.service``
-------------------

Make sure ``haproxy`` service is running.
