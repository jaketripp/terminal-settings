# terminal-settings

Pretty terminal image

Make your terminal have a theme that is easy on the eyes and increase your terminal history so that you can search for stuff.

1. Download the Solarized Dark Higher Contrast.terminal file
2. Right click on downloaded file and click open and agree to permissions.
3.  Open Terminal and type 
```
nano .bash_profile
```
4.  Paste in the following lines:
```
export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
alias ls='ls -GFh'
export HISTFILESIZE=2000
```
5. Hit **Control+O** to save, then **Control+X** to exit out of nano.
6. Restart terminal
7. Click **Terminal** > **Preferences**, then make sure your **Text** and **Window** tabs look like this.
img
img
8. You may need to restart your terminal again.
9. Enjoy!
