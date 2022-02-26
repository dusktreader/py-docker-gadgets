************
 Change Log
************

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

v0.1.1 - 2022-02-25
-------------------
* Added tmpfs option to ``start_service``

v0.1.0 - 2022-02-22
-------------------
* Moved functions to standalone tools module
* Made Buzz re-use these methods
* Changed ``handle_errors`` ``exception_class`` parameter to ``handle_exc_class``
* Changed ``handle_errors`` to send ``DoExceptParams`` as a single parameter
* Removed ``sanitize_err_string`` as it should not be needed after 2.0.0
* Added a Makefile for running quality checks easier.
* Updated examples.
* Updated docs a lot.
* Dropped support for Python 3.6

* Initial version of ``py-docker-gadgets``
- Added README and CHANGELOG
- Added source code
- Set up project using ``poetry``
