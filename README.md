tmux-config
===========

tmux configuration script.

Installation
------------

# Copy the desired files into user home, adding a leading period (".").

    if [ -f ~/.tmux.conf ]
    then
      cp -p ~/.tmux.conf ~/.tmux.conf.save.$(date +%Y%m%d-%H%M%S)
    fi
    cp -pi tmux.conf ~/.tmux.conf

   Or use the included script.

# Start tmux or reload the configuration in an existing tmux session.

	:source-file ~/.tmux.conf

	- or in a shell -

	$ tmux source-file ~/.tmux.conf

Reference
---------

http://superuser.com/questions/360832/how-can-i-make-ctrlleft-right-keys-work-right-in-tmux
 
