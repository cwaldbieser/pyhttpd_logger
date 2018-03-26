==============
PyHttpd Logger
==============

Ever trying to stand up some proxied web service and you can't figure out what
headers are being sent along in the request from the proxy to the back end
service?

The PyHttpd Logger script can create a mini web server that will accept HTTP
requests on a port and display the headers.  It uses the Python3 Standard
Library, so the script is quite simple to deploy and is very portable.


Example:

.. code::shell

    $ ./httpd_logger.py 8000

