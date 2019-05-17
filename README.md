# This is didactic-bassoon

git@github.com:lardellin/didactic-bassoon.git

Wifi: Gast
Psw: 123aa999 

In this tutorial we will answer the question: 'Why should you care about Python?'

* Installing things
We will be installing *python* and *jupyter-notebook*
  * Linux
  
  Depending on your favorite distro run
  
  ```bash 
  sudo [apt install / yum install / pacman -S ] 
  python pip 
  ```
  This will install both the python interpreter and pip, which is a
  usefull package manager for python libraries. After this install
  jupyter-notebook, and a couple of python libraries
  ```bash
  sudo pip install jupyter-notebook numpy scipy pandas
  ```
  
  * Mac OS
  
  Install Homebrew (https://brew.sh/): 
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

```brew install python 
python -m pip install jupyter-notebook numpy scipy pandas
```
  * Windows
Install bash shell command-line tool:
 - Open Settings.
 - Click on Update & security.
 - Click on For Developers.
 - Under "Use developer features", select the Developer mode option to setup the environment to install Bash.
 - On the message box, click Yes to turn on developer mode.
 - After the necessary components install, you'll need to restart your computer.
 - Once your computer reboots, open Control Panel.
 - Click on Programs.
 - Click on Turn Windows features on or off.
 - Check the Windows Subsystem for Linux (beta) option.
 - Click OK.
 - Restart now
 - run bash.exe
 - Follow Linux instructions 
