####################################################
Starter files for building application documentation
####################################################


See the `Documentation for documenting applications
<http://application-documentation.readthedocs.org>`_ for more guidance on building and writing
documentation.


******************************
How to use these starter files
******************************

For a brand-new project
=======================

* Follow the directions for `setting up <http://application-documentation.readthedocs.org>`_ and
  then `configuring <http://application-documentation.readthedocs.org>`_ your documentation.

* ``git clone git@github.com:divio/application-documentation-starter-files.git`` (i.e. this
  repository) into another directory.

* Copy the *contents of* (i.e. not the directory itself) the ``starter-docs`` directory of this
  project into your project's ``docs`` directory.

* Copy the ``STARTER-README.rst`` file into your project, and rename it to ``README.rst``


For a project that has some of these files already
==================================================

Your work will be a little harder; you'll have to choose which files to copy/overwrite/rewrite
individually.


Search-and-replace
==================

The starter files contain strings you can replace with the correct ones for your application. Do a
search-and-replace on them:

* ``application-full-name``: the full, human name of the application - e.g. ``Aldryn Spaceship``
* ``application-package-name``: the package name - e.g. ``aldryn-spaceship``
* ``application-python-name``: the Python name - e.g. ``aldryn_spaceship``
* ``application-repo-url``: the URL of the repository - e.g.
  ``https://github.com/aldryn/aldryn-spaceship``

After your search and replaces, you will still need to go through the documentation to check and
correct:

* line wrapping changes
* underline/overlne of headings


Provide actual content
======================

Throughout the starter files you will see text in square brackets, e.g.``[describe what the
application does]`` - these are things you need to do.
