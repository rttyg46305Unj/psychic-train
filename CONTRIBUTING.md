# contribution rules
## safety
please make all compiled files safe.
## compilation
### python
use pyinstaller.
compile normal swzlr using the flags:
```--onefile --icon=swzlr.ico --hiddenimport libswzl2```
and for swzlr-gui:
```-windowed --onefile --icon=swzlr.ico --hiddenimport libswzl2```
but if you want to debug if you're modifying swzlr-gui, use the normal swzlr flags.
### c and js
use gcc or node.js. either way.
## file name rules
it can either be
```filename-yyyymmdd```
or
```filename-yyyymmddhhmmss```
but you can also do it without the dash.
### what if its too big?
compress and seperate it into 25 mb chunks using the filenames ```filename.7z.###``` or ```filename.part#.rar```
this does mean you can only use 7zip or winrar, but i hope it works for you.
