# terminal-settings

![My terminal](https://github.com/jaketripp/terminal-settings/blob/master/terminal.png "My terminal")

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
![Terminal Preferences Text tab](https://github.com/jaketripp/terminal-settings/blob/master/text.png "Terminal Preferences Text tab")
![Terminal Preferences Window tab](https://github.com/jaketripp/terminal-settings/blob/master/window.png "Terminal Preferences Window tab")
8. You may need to restart your terminal again.
9. Enjoy!

Theme: https://github.com/lysyi3m/osx-terminal-themes

.bash_profile stuff: http://osxdaily.com/2013/02/05/improve-terminal-appearance-mac-os-x/
