
Readme file for the course-tree-access block
=============================================

A plugin for the learning management system moodle to provide individual 
course assortment for its users.

- @package    block_course_tree_list
- @copyright  2012 Jay Huber <jhuber@colum.edu>
- @license    http://www.gnu.org/copyleft/gpl.html GNU GPL v3 or later


Description
-----------
This plugin addresses the navigation problem for users that are enrolled in a 
lot of courses on a moodle site.

The hierarchy expands to courses in progress, and will display based on admin 
settings to display active courses for x number of weeks before they start
and after they complete.

It builds a hierarchy collapsable/expandable menu based on the categories.
The menu was designed entirely with CSS and does not use any javascript for its function.


Code Location
-------------
You can always find the latest version at: https://github.com/jayhuber/course_tree_list
Moodle plugins will notify you as I update the code on Moodle.org


Bug Reports
-----------
Report all bugs on https://github.com/jayhuber/course_tree_list/issues


Installation
------------
- Copy the "course_tree_list" folder into the "moodle/blocks" directory
- Visit your moodle site in a browser, logged in as an administrator.
- Go to "Site Administration > Notifications > Continue"
- Add the "course-tree-access" block. 

Currently, No Tables are created for the use of this block.

Changelog
---------
v2012110800:
- Initial Version

Release notes
-------------
v2012110800:
- Release Canditate