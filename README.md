Free Room Finder
================


Tired of Rooms on Campus Always Being in Use?
---------------------------------------------

We feel your pain, the Free Room Finder is here to solve that by finding free
rooms on campus during the time or duration you need a room and given the date
you need a free room.


What the Free Room Finder Does Well
-----------------------------------

Find all free rooms on campus according to a detailed internal list of every course
at UOIT/DC and by finding free time slots for rooms by determining times when
they are not being used for any classes.


What the Free Room Finder Doesn't Do Well
-----------------------------------------

Detect students who may have already found the free room before you and are using it.
*(Don't panic we've got this one solved! We need help setting up a room booking system
for students who use the service.)*

Detect clubs and other organizations who may have booked the room through other school
organizations such as the SA, Campus Societies, or the mob.


How to Setup the Free Room Finder
----------------------------------

If you are interested in setting up the free room finder for development purposes or 
if you would like to host it yourself, the setup procedure is fairly straighforward.
Please see the detailed setup instructions in [SETUP.md](SETUP.md), which provides 
instructions on creating the database, configuring the PHP source files, and lastly 
a description of useful source files and their purpose.


How You Can Contribute
----------------------

While the database, data collection scripts for getting all courses on campus, the scripts
for analyzing the data to find free rooms, and website are mostly complete there is still
much to be done, such as:

+ Fixing up parsing errors in the screen scraping scripts (scripts/db-generate-room.py)
as it currently does not work properly for screen-scraping course info for every year.
+ Detecting students who may have already found the free room before you and are using it, 
such as adding support for a room booking system so you can see how many students have already
booked the room through the free room finder website.
+ An effective solution to determine clubs and other organizations who may have booked the room 
through other school organizations such as the SA.
+ Code refactoring and documentation, we are leaning towards [Sphinx](http://sphinx.pocoo.org/)
for the Python code, [phpDocumentor](http://www.phpdoc.org/) for the PHP source code, and 
[Read the Docs](http://readthedocs.org/) or even a wiki for everything else would be great.


Copyright (Really Copyleft)
---------------------------

The Free Room Finder mobile application, scripts, and other source files where the 
copyright notice is indicated, are licensed under the 
[GNU General Public License, Version 3](http://www.gnu.org/licenses/gpl.html).

The Free Room Finder Website uses the [GNU Affero General Public License, Version 3]
(http://www.gnu.org/licenses/agpl-3.0.html) to ensure that the source code for the 
website is also provided. This prevents a loop-hole that exists in the GPL where a 
website can be based off open source code but the actual "open source" code for the
websiteis not provided. 

Under the AGPLV3 that this software is licensed under you must ensure that the source 
code that you are using is made publicly available and accessible to everyone. In the
case of the Free Room Finder Website a URL to this GitHub page where the source code 
can be obtained is provided in the footer of the website.
