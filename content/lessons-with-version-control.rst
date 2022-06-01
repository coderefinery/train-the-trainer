Lesson development with version control
=======================================

So, we want to practically share.  We have these minimum requirements:

* Someone can get the preferred form of modification, to improve
  without limitation.

* It is trivial to track differences and send the changes back to the
  source, with little cost to the original maintainer.

Especially with the second of these, version control in an online
platform seems to be the only reasonable option.



Primary articles
----------------

(none yet)



Summary
-------

CodeRefinery and the Carpentries use git and Github to develop
lessons.  The general procedure is this:

* Version control to store the raw files in text format.
* A static website compiler to convert them to HTML files
* Serving to the public via Github Pages (but this could be replaced
  with other systems)

This allows for true collaborative development and community
contributions.

Carpentries uses a custom website complierer based on R, CodeRefinery
uses the Sphinx documentation engine which is used in many different
projects for documentation.  CodeRefinery's use of a standard tool
allows us to build on a huge and growing ecosystem of extensions and
themes, and promotes local reuse.

The exact static website generator used isn't so important, as long as
some form of version control is used.



See also
--------

TODO: actual reference
