### Emacs Euslisp Mode

euslisp-mode is a major mode for editing Euslisp code(https://github.com/euslisp/EusLisp).
euslisp-mode is free software, licensed under the GNU GPL.

The latest stable version is euslisp-mode 0.0.7, released on July, 2017.

## installation
Make sure to place euslisp-mode.el somewhere in the load-path and add the following lines to your .emacs file to associate euslisp-mode with .l files:

```
(require 'euslisp-mode)
```

If you want to set catkin source path, please execute '''(euslisp-change-env)''' or write a following codes in init.el.

```
(euslisp-change-env "/opt/ros/indigo")
(euslisp-change-env "/PATH/TO/CATKIN_WORKSPACE")
```
