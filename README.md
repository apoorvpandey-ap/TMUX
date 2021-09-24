1. ## session management
1. tmux ls (or tmux list-sessions)
1. tmux new -s session-name
1. Ctrl-b d Detach from session
1. tmux attach -t [session name]
1. tmux kill-session -t session-name


1. Ctrl-b c Create new window
1. Ctrl-b d Detach current client
1. Ctrl-b l Move to previously selected window
1. Ctrl-b n Move to the next window
1. Ctrl-b p Move to the previous window
1. Ctrl-b & Kill the current window
1. Ctrl-b , Rename the current window
1. Ctrl-b q Show pane numbers (used to switch between panes)
1. Ctrl-b o Switch to the next pane
1. Ctrl-b ? List all keybindings

1. ## moving between windows
1. Ctrl-b n (Move to the next window)
1. Ctrl-b p (Move to the previous window)
1. Ctrl-b l (Move to the previously selected window)
1. Ctrl-b w (List all windows / window numbers)
1. Ctrl-b window number (Move to the specified window number, the
1. default bindings are from 0 -- 9)

1. ## Tiling commands
1. Ctrl-b % (Split the window vertically)
1. CTRL-b " (Split window horizontally)
1. Ctrl-b o (Goto next pane)
1. Ctrl-b q (Show pane numbers, when the numbers show up type the key to go to that pane)
1. Ctrl-b { (Move the current pane left)
1. Ctrl-b } (Move the current pane right)

1. ## Make a pane its own window
1. Ctrl-b : "break-pane"

1. ## add to ~/.tmux.conf
1. bind | split-window -h
1. bind - split-window -v

1. Link https://www.youtube.com/watch?v=f1Gqc3JWBBI** 
