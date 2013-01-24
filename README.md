svn-export-changes.sh
=====================

Bash script for exporting svn files from a range of revisions

It can sometimes be a pain to export just modified files from SVN on the MAC/*nix machines. 

TortoiseSVN on windows has [a simple method for this]
(http://verysimple.com/2007/09/06/using-tortoisesvn-to-export-only-newmodified-files/)

This script is for everyone else.

Usage
--

Download this and chmod 755 it. Add it to your bin if you so desire, then it's as simple as 

`svn-export-changes repo-location`

The script will pull the changes to that repository between the HEAD and PREV and put it in a directory called 'export' (relative to the script location)

You can pass in a range of revisions and a location to export to.

`svn-export-changes repo-location revision-from revision-to export-directory`

That's it.

Portions taken from [this post](http://www.electrictoolbox.com/subversion-export-changed-files-cli/) Thanks to Chris Hope.




*"...there's a bash for that..."*
