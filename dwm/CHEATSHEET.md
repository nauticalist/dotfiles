e are the default keyboard bindings.
M (Mod) should be Alt.
C is Control.
S is Shift.

M+p		spawn dmenu
M+S+Return	spawn a terminal
M+Space		toggle layout
M+S+Space	toggle floating of client
M+C+s		toggle sticky (client visible on every workspace)
M+b		toggle status bar visibility
M+j		focus next client
M+k		focus previous client
M+g		decrease main window/stack ratio
M+s		increase main window/stack ratio
M+a		pop window from stack ("deiconify")
M+d		push window to stack ("iconify")
M+C+y		add new workspace
M+C+r		remove current workspace (push current windows to stack)
M+m		toggle maximization of client
M+Return	zoom window
M+Tab		focus next window
M+S+Tab		focus previous window
M+S+c		kill window
M+l		view previous workspace
M+h		view next workspace
M+S+l		move window to next workspace
M+S+h		move window to previous workspace
M+C+l		move mouse pointer to next screen (xinerama only)
M+C+h		move mouse pointer to previous screen (xinerama only)
M+S+s		move all clients one screen around (xinerama only,
  		     effectively swaps screens on dual-monitor setup)
M+1		view workspace 1
M+2		view workspace 2
[...]
M+0		view workspace 10
M+S+1		move window to workspace 1
M+S+2		move window to workspace 2
[...]
M+S+0		move window to workspace 10
ScrollLock	toggle locked mode (deactivate all keybindings)


These are the default mouse button bindings.

  click on workspace display:
left button     view next workspace
right button    view previous workspace
left button+M   add new workspace
right button+M	remove current workspace (push current windows to stack)
scroll up       view next workspace
scroll down     view previous workspace

  click on layout symbol:
left button     toggle layout
right button    toggle layout (backwards)
scroll up       toggle layout
scroll down     toggle layout (backwards)

  click on window title in status bar:
left button     focus next client
right button    focus previous client
scroll up       focus next client
scroll down     focus previous client

  click on status text in status bar:
left button     volume up (needs amixer)
right button    volume down (needs amixer)
scroll up       volume up (needs amixer)
scroll down     volume down (needs amixer)

  click on root window:
left button spawn a terminal
