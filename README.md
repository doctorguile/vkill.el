# vkill.el

vkill.el by Kyle E. Jones, Noah S. Friedman

http://www.splode.com/~friedman/software/emacs-lisp/src/vkill.el

Hosting a copy here for straight.el or elpaca installation


    M-x vkill creates a buffer containing ps(1) output and allows you to
    mvoe around in it marking processes to be sent a signal.  Type a `?'
    in the Process Info buffer for more help.
    
    The commands vkill and list-unix-processes are the package entry points.
    
    To autoload, use
        (autoload 'vkill "vkill" nil t)
        (autoload 'list-unix-processes "vkill" nil t)
    in your .emacs file.
