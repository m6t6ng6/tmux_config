TMUX CONFIG FOR MAC:

# tmux installation:
brew install tmux

# tmux config:

https://www.youtube.com/watch?v=7gmpjacFoHM&list=PL7XhXl__0BHiVnQMPyNqTZ3vo-XwMW_TU

# copy file tmux.conf to:
$HOME/.config/tmux/tmux.conf

# get into tmux:
tmux

# configure tmux to use the in such directory

press "Ctrl + b"  (release keys -- nothing will happen)

press ":"  (green bar in the bottom will turn into yellow/ orange)

paste "source-file ~/.config/tmux/tmux.conf"   (automatically will use the new file)

<img width="1119" height="26" alt="image" src="https://github.com/user-attachments/assets/6a7abf83-a4d1-4c52-9be9-bfff7b5242c4" />

# import file via iterm2:
iterm2_tmux_hexa_codes.itermkeymap

<img width="911" height="591" alt="image" src="https://github.com/user-attachments/assets/8c6d6308-35ff-4663-b2e1-2b8c594ef980" />


shutdown iterm2 and execute it back


# KEY BINDINGS:

SHIFT + COMMAND + ENTER ---- CREATE A NEW WINDOW

COMMAND + ENTER ---- MOVE WINDOW TO THE PRIMARY VIEW

COMMAND + L ---- RESIZE TO LEFT

COMMAND + H ---- RESIZE TO RIGHT

COMMAND + K ---- CYCLE AMONG WINDOWS TO THE RIGHT

COMMAND + J ---- CYCLE AMONG WINDOWS TO THE LEFT

COMMAND + M ---- MAXIMIZE ACTIVE WINDOW

SHIFT + COMMAND + R ---- CLOSE ACTIVE WINDOW

COMMAND + U ---- COPY MODE IN TERMS TO MOVE ALONG THE OUTPUT OF THE WINDOW

SHIFT + COMMAND + U ---- SWAP AMONG VERTICAL AND HORIZONTAL VIEWS
