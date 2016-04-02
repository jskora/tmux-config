# tmux-config

tmux configuration script.

## Installation

### Install configuration in home directory
Copy the config file prefixing the filename with a period (".")
```
if [ -f ~/.tmux.conf ]; then
  cp -p ~/.tmux.conf ~/.tmux.conf.save.$(date +%Y%m%d-%H%M%S)
fi
cp -pi tmux.conf ~/.tmux.conf
```
or use the included script do the copy.
```
./setup.sh
```    
### To reload the configuration in an existing tmux session
Use the tmux command
```
:source-file ~/.tmux.conf
```
or the CLI command.
```
tmux source-file ~/.tmux.conf
```

#### Reference
http://superuser.com/questions/360832/how-can-i-make-ctrlleft-right-keys-work-right-in-tmux
 
