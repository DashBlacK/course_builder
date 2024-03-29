# course builder
Course Builder was born in July 2012 when we hosted a 2-week online,
community-based course called Power Searching with Google. The course showcased
search techniques and how to use them to solve real, everyday problems. We
created Power Searching as a MOOC (Massive Open Online Course) by using a
variety of Google's existing products and by writing an App Engine application
for the course material and assessments.

After running Power Searching, we decided to open source the code and provide
documentation so others could replicate this experiment by creating and running
their own courses.

For more information on Course Builder, see the documentation at
https://edu.google.com/openonline/course-builder/index.html

Course Builder uses an HTML5 icon (found at
coursebuilder/modules/core_tags/resources/html5-badge-h-solo.png)
from w3.org, as licensed under the Creative Commons Attribution 3.0 Unported
license version. For more information on HTML5, see http://www.w3.org/html5

Course Builder also uses several Material icons provided by Google under the
Apache 2.0 license.

Course Builder automatically downloads a number of third-party libraries. Some
are for use during development and deployment of software.  These are stored in
your home directory under coursebuilder_resources_<version>.  Other libraries
are included and deployed when your application is pushed to the App Engine
servers.  These libraries are placed in a lib/ directory alongside the Course
Builder source files.  All of these third-party packages are governed by their
respective licenses found in the packages' respective directories or .zip files.

## setup 
- `rm lib/_static/`
- `sh ./scripts/start_in_shell.sh -f -s`
- login with anything as admin
- add a course
- Setting - advacned site settings - set `gcb_enable_course_explorer_page` to `true` 

