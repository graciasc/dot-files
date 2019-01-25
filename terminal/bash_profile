  1 ### Aliases
  2 
  3 
  4 
  5 # Open specified files in Sublime Text
  6 # "s ." will open the current directory in Sublime
  7 alias subl='open -a "Sublime Text"'
  8 alias phpini='cd /usr/local/etc/php/7.1; subl php.ini'
  9 
 10 # Color LS
 11 colorflag="-G"
 12 alias ls="command ls ${colorflag}"
 13 alias l="ls -lF ${colorflag}" # all files, in long format
 14 alias la="ls -laF ${colorflag}" # all files inc dotfiles, in long format
 15 alias lsd='ls -lF ${colorflag} | grep "^d"' # only directories
 16 
 17 # Quicker navigation
 18 alias ..="cd .."
 19 alias ...="cd ../.."
 20 alias ....="cd ../../.."
 21 alias .....="cd ../../../.."
 22 
 23 # Shortcuts to my Code folder in my home directory
 24 alias code="cd ~/Code"
 25 alias sites="cd ~/Code/sites"
 26 
 27 # Enable aliases to be sudo’ed
 28 alias sudo='sudo '
 29 
 30 # Colored up cat!
 31 # You must install Pygments first - "sudo easy_install Pygments"
 32 # alias c='pygmentize -O style=monokai -f console256 -g'
 33 
 34 
 35 ### Prompt Colors
 36 # Modified version of @gf3’s Sexy Bash Prompt
 37 # (https://github.com/gf3/dotfiles)
 38 if [[ $COLORTERM = gnome-* && $TERM = xterm ]] && infocmp gnome-256color >/dev/null 2>&1; then
 39         export TERM=gnome-256color
 40 elif infocmp xterm-256color >/dev/null 2>&1; then
 41         export TERM=xterm-256color
 42 fi                                                                                                                                                                                                      
 43 
 44 if tput setaf 1 &> /dev/null; then
 45         tput sgr0
 46         if [[ $(tput colors) -ge 256 ]] 2>/dev/null; then
 47                 BLACK=$(tput setaf 190)
 48                 MAGENTA=$(tput setaf 9)
 49                 ORANGE=$(tput setaf 172)
 50                 GREEN=$(tput setaf 190)
 51                 PURPLE=$(tput setaf 141)
 52                 WHITE=$(tput setaf 0)
 53         else
 54                 BLACK=$(tput setaf 190)
 55                 MAGENTA=$(tput setaf 5)
 56                 ORANGE=$(tput setaf 4)
 57                 GREEN=$(tput setaf 2)
 58                 PURPLE=$(tput setaf 1)
 59                 WHITE=$(tput setaf 7)
 60         fi
~/.bash_profile                                                                                                                                                                                     42,2 Top

                                                                                                                                                                                                   
