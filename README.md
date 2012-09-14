githubiverse-template
============

This is a Github Page template to show off your 3D printer model or project.  Inspiration clearly taken from the excellent Thingiverse.

Instructions
------------

* Create a github project.
* Add and commit content (sources, stl files, images), into separate folders.
* Create an empty gh-pages branch. See http://pages.github.com for further information.
* Copy (not clone!) the contents of this githubiverse-template project into the root directory of the gh-pages branch.
* Edit _config.yml: Define metadata about the project and edit the preferences as required.
* Edit index.md: Add a description, in markdown format, in the bottom section, or alternatively, use the description_file option in _config.yml to use file contents from the project root.
* Optionally, modify the html and css to suit your tastes.
* Test locally with jekyll, or commit and push to github.
* When pushed, view at http://yourusername.github.com/yourprojectname, an example project can be seen here: http://garyhodgson.github.com/githubiverse-tst


Alternative Method
------------------

* Follow the instructions above but instead of copying the contents of githubiverse-template, create a submodule for the gh-pages branch into a folder called, for example, template.  I.e. `git submodule add -b gh-pages git://github.com/garyhodgson/githubiverse-template.git template`  Make sure to use the git read-only url syntax, i.e. git://...
* Copy the _config.yml file from the template folder to the root folder and add the following at the top: `source: template`

This has the benefit that the submodule can be updated without having to copy the new files in each time.  One could fork githubiverse-template, edit it to your taste, and then use it as a submodule in all your 3D printing projects.  Updating the shared template would mean only having to update the submodule in each project.

License
-------
GPL3