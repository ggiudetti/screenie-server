2.0.0 / 30-01-2018
==================

This is a major release which might require some more manual setup of
Chromium to make use of. Don't upgrade to this before you've *checked the
requirements* of Chromium/Puppeteer, particularly when it comes to sandbox
support in your kernel for security.

* Switches to Chromium through Puppeteer over PhantomJS
* Support a custom delay after page load before screenshot is generated
* Support flag for enabling file protocol URLs

1.2.0 / 16-10-2017
==================

* Add basic logging functionality
* Handle SIGTERM gracefully, draining the pool
* Added Dockerfile with CA certificate updates

1.1.0 / 17-03-2017
==================

* Add PDF output support
* Add support to customize the output format with a `format` request parameter

1.0.0 / 06-02-2017
==================

* Initial public release
