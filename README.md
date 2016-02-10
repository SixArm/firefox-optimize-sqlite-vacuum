# Firefox script to optimize SQLite by using vacuum to delete stale data.

Credit: http://ubuntuforums.org/showthread.php?t=1193567

Firefox stores a lot of data, for example bookmarks, in database files.
The files are in your profile directory and have the extension .sqlite.

This script looks for sqlite database files in your `~/.mozilla` folder,
then executes the sqlite vacuum command, which removes stale data.

## About

  * Command: firefox-optimize-sqlite-vacuum
  * Version: 1.1.0
  * Created: 2010-05-20
  * Updated: 2015-01-25
  * License: GPL
  * Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)
