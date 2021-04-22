# Git Touch

Shell script that gets the last date and time the repository changed,
and uses the touch(1) command to recursively change the access and
modification times to that date and time.

The intent is to set the access and modification dates for new clones
of really old repositories.


Example:
```
$ git touch
```
