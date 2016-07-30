# autorun-emacs
Bash script to auto-start emacs after checking if it is already running.

This simple script checks whehter emacs process is already running or not.
If emacs process is not running, then it will start a emacs --daemon process in the background. 

## Usage
You could place this in the config file of your shell to run on startup. 
I use ZSH for instance and have placed this script in my zshconfig file so that everytime I open a new terminal session, it checks whehter emacs is running or not and restart if it is not running. 

Disclaimer:
This is still the very first version. Implementation might not be optimal for all usage. 
