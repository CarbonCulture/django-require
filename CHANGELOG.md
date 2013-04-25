django-require changelog
========================


1.0.3 - 25/04/2012
------------------

* Added ability to specify custom compiler environments, either by class name or alias.
* Added default 'auto' environment alias, which uses 'node' if available, else 'rhino'.
* Updating requirejs to 2.1.4


1.0.2 - 25/02/2012
------------------

* Not adding build profiles to REQUIRE_EXCLUDE during compilation, to speed up redeploys to remote filesystems.
* Updating requirejs to 2.1.4
* Updating almond to 0.2.5
* Updating closure compiler to r2388 
* Updating rhino to 1.7R4.


1.0.1 - 30/11/2012
------------------

* Support for running the optimizer using node (much faster).
* Updating to RequireJS 2.1.2 and almond 0.2.1
* Better error message when no STATICFILES_DIRS are defined.


1.0.0 - 01/11/2012
------------------

* First production release.