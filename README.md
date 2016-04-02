tmux-config
===========

tmux configuration script.

Installation
------------

1. Copy the configuration file into user home with a leading period ("."), or use the included script do the copy.
 ```
     if [ -f ~/.tmux.conf ]; then
       cp -p ~/.tmux.conf ~/.tmux.conf.save.$(date +%Y%m%d-%H%M%S)
     fi
     cp -pi tmux.conf ~/.tmux.conf
```
2. To reload the configuration in an existing tmux session either use tmux command
    ```
:source-file ~/.tmux.conf
```
or the CLI command.
```
tmux source-file ~/.tmux.conf
```

Reference
---------

http://superuser.com/questions/360832/how-can-i-make-ctrlleft-right-keys-work-right-in-tmux
 
