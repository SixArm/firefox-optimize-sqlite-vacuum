# Firefox shell script:<br>optimize SQLite by running vacuum

Syntax:

    firefox-optimize-sqlite-vacuum

Credit: http://ubuntuforums.org/showthread.php?t=1193567

Firefox stores a lot of data, for example bookmarks, in database files.
The files are in your profile directory and have the extension .sqlite.

This script looks for sqlite database files in your `~/.mozilla` folder,
then executes the sqlite vacuum command, which removes stale data.
