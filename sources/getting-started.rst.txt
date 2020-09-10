===============
Getting Started
===============

Zenora can be installed be Python's package manager, pip:

``$ pip install zenora``

.. note::
    This library is dependent on Requests and so naturally will only be available for Python
    versions that Requests also supports.


Accessing the API
=======================

Your first API usage can be written in just a few lines of code:
::

    # Import the library
    import zenora

    # Instantiate a REST API instance
    api = zenora.RESTAPI(token="your_token_here", token_type="your_token_type_here")

    # Query API for getting channel
    # Zenora parses API response into Python objects for accessing data
    channel = api.get_channel(732595879747256371)

    # Use the data
    print(channel.name)


.. note::
    There are two types of tokens, ``Bot`` & ``Bearer``. Bot tokens are used for accessing the API in bot applications
    Bearer tokens are used for accessing the API data on behalf of a user account for purposes such as Oauth2.
