KuaiNiu Auth for Sentry
======================

An SSO provider for Sentry which enables KuaiNiu authentication.

Install
-------

::

    $ pip install https://github.com/kuainiu/sentry-auth-kuainiu/archive/master.zip

Setup
-----

Start by `creating a project in the KuaiNiu Developers Console`_.

In the **Authorized redirect URIs** add the SSO endpoint for your installation::

    https://sentry.example.com/auth/sso/

Finally, obtain the API keys and plug them into your ``sentry.conf.py``:

.. code-block:: python

    KUAINIU_CLIENT_ID = ""

    KUAINIU_CLIENT_SECRET = ""

