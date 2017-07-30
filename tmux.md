# Sessions
Creating a session:

    tmux 

List sessions:
    
    tmux ls
    
Attach to a session:

    tmux attach -t work
    
Kill session:

    tmux kill-session -t myname

Detach from a session: 

    C-b d

# Windows
Create a window:

    C-b c          create a new window

Switch between windows:

    C-b 1 ...      switch to window 1
    C-b w          choose window from a list
    C-b &          kill window
    
# Panes

    C-b "          split horizontally
    C-b %          split vertically

    C-b <arrow>    go to the next pane
    C-b o          go to the next pane 
    C-b x          kill the current pane

Main references: https://gist.github.com/andreyvit/2921703 and https://gist.github.com/MohamedAlaa/2961058
