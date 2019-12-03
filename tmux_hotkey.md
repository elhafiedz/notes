# tmux hotkeys

pre : ctrl + b (default)

## sessions
- create new session 		: $tmux new -s (session name)
- attach to a session		: $tmux attach -t (session name)
- detatch active session	: pre + d
- list sessions	: 
	- $tmux list-sessions
	- $tmux ls
- rename active session		: pre + $
- kill a session		: $tmux kill-session -t (session name)

## windows
- create new window		: pre + c
- move to next/previous window :
	- pre + n/p
	- pre + window index
- rename window 		: pre + ,
- list window			: pre + w
- close focused window		: pre + &

## panes
- split vertically/horizontally	: pre + (%/")
- move to next/previous pane : 
	- pre + (o/;)
	- pre + arrows to move freely
- change pane layout		: pre + space
- zoom in/zoom out pane		: pre + z
- close focused pane :
	- ctrl + d
	- $exit
- resize pane			: pre + (hold ctrl + arrows) 

