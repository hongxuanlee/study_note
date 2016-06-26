## tmux shortcut 
### Via shortcut
```
Ctrl-b s
```
### via tmux command
```
tmux ls
```
### into tmux command mode
```
:
```
### create a new session
```
tmux new -s session-name
tmux new
```

### attaching to an existing session
```
tmux a // connect you to the first available session
tmux a -t session-name
```

### detaching from a session
```
tmux detach
// or shortcut
Ctrl-b d 
```

### killing a session
```
tmux kill-session -t session-name
```

### configuration
* ~/.tmux.conf
* see ./tmux.conf

### windows
* `c` create a new window
* `,` rename the current window
* `q` command-prompt "move-window -t '%%'"
* `w` list windows
* `%` split horizontally
* `"` split vertically
* `n` change to the next window
* `p` change to the previous window
* `0 to 9` select windows 0 through 9

### Panes
* `%` create a horizontal pane
* `"` create a vertical pane
* `q` show pane numbers
* `o` toggle between panes
* `}` swap with next pane
* `{` swap with previous pane
* `!` break the pane out of the window / force quit current pane
* `x` kill the current pane, it's will ask Y/N
* `q` show pane list 


