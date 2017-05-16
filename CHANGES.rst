=======
CHANGES
=======

4.0.0 (2017-05-16)
------------------

- Add support for Python 3.4, 3.5, 3.6 and PyPy.


3.5.3 (2010-09-01)
------------------

- Removed the dependency on zope.app.publisher, added missing dependencies.
- Replaced the use of zope.deferredimport with direct imports.


3.5.2 (2009-01-22)
------------------

- Removed zope.app.zapi from dependencies, replacing its
  uses with direct imports.

- Clean dependencies.

- Changed mailing list address to zope-dev@zope.org, changed
  url from cheeseshop to pypi.

- Use zope.ManageServices permission instead of zope.ManageContent
  for errorRedirect view and menu item, because all IErrorReportingUtility
  views are registered for zope.ManageServices as well.

- Fix package's README.txt


3.5.1 (2007-09-27)
------------------

- rebumped to replace faulty egg


3.5.0
-----

- Move core components to ``zope.error``


3.4.0 (2007-09-24)
------------------

- Initial documented release
