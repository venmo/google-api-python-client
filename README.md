This is a fork of https://github.com/google/google-api-python-client with the changes from https://github.com/google/google-api-python-client/pull/146.

This fixes problems when using google's library as a setuptools dependency along with uritemplate.py.
For more details, see these issues:
* ["uritemplate.py" conflicts with "uritemplate" package](https://github.com/sigmavirus24/uritemplate/issues/14)
* [Switch from "uritemplate" to "uritemplate.py"](https://github.com/google/google-api-python-client/issues/57)

To install, use `pip install google-api-python-client-uritemplate`.
