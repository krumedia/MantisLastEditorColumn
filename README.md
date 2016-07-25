MantisLastEditorColumn
===============

Adds the Tags column to views in the Mantis bug tracker

#MantisLastEditorColumn

## Copyright
Original version copyright 2010, Brian Enigma, <http://netninja.com/projects/tagcolumn/>

Code for improved CSV, Excel export contributed by Albie Janse van Rensburg, December 2013

Edited to show last editor instead of tags by Matthias Blümel, July 2016

Licensed under the GNU General Public License.

##USAGE

After installation (see below), users can add the "LastEditor" column to their
View Issues screen by following these steps.

1. Go to My Account -> Manage Columns.
2. Add the "lasteditorcolumn_lasteditor" column to your View Issues Columns.

An administrator can perform similar steps, but under Manage -> Manage 
Configuration -> Manage Columns to add this column for all users.

##REQUIREMENTS

Mantis 1.3.0 or greater is required.

Note that this version of the plugin does not support the column data
caching API.  This means that there could be some performance penalties
when run on high-traffic sites.

##INSTALLATION

Installation is simple and involves creating a plugin folder and copying the
plugin's PHP file into the folder.  You then activate it from within Mantis.

1. Create a folder under your mantis plugins folder named LastEditorColumn.
   For instance, if you have Mantis installed at /var/www/mantisbt, then
   you would create /var/www/mantisbt/plugins/LastEditorColumn.
2. Copy LastEditorColumn.php into this folder.
3. Log in to Mantis as an administrator.
4. Go to Manage -> Manage Plugins and click "Install" next to TagColumn.

Once installed, you can use it as described in the "Usage" section, above.

Have fun!

