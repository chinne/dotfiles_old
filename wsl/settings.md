    To disable the beep in bash you need to uncomment (or add if not already there) the line set bell-style none in your /etc/inputrc file.
    Note: Since it is a protected file you need to be a privileged user to edit it (i.e. launch your text editor with something like sudo <editor> /etc/inputrc).
