=========
Changelog
=========

v1.0.2 - 12/08/2016
===================

* Tests for Django 1.10 compatibility.


v1.0.1 - 24/07/2016
===================

* Add tests and support for Django 1.9 and Python 3.5.
* Drop support for Python 2.5, 2.6, Django 1.4, 1.5, 1.6.
* Fix AttributeError when content_type is None, issue `#21 <https://github.com/yprez/django-logentry-admin/issues/21>`_.
* Show log entries for users with change_logentry permission, `#25 <https://github.com/yprez/django-logentry-admin/pull/25>`_.
* Test with py.test instead of unittest.


v0.1.5 - 17/02/2015
===================

* Django 1.8 compatibility.


v0.1.4 - 28/09/2014
===================

* Added Django 1.7 compatibility.
* Fixed compatibility issues with Django 1.5, 1.4 and Python 3.2.
* Added tests.


v0.1.3 - 02/06/2014
===================

* Improved display layout.
* Added links to user and object.
* Added "By staff user" filter.
* Don't allow delete action for LogEntry.
* Better performance by prefetching content types.


v0.1.2 - 26/08/2013
===================

* Added an empty model.py file.
* Minor documentation (readme) updates/fixes.


v0.1.1 - 28/12/2011
===================

* Added object links and action description.


v0.1.0 - 26/12/2011
===================

* Initial release.
