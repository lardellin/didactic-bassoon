# This is didactic-bassoon

without ssh-key: `git clone https://github.com/lardellin/didactic-bassoon.git`

over ssh (see how to [generate](https://help.github.com/en/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key) and [add](https://help.github.com/en/enterprise/2.15/user/articles/adding-a-new-ssh-key-to-your-github-account) a ssh-key): `git clone git@github.com:lardellin/didactic-bassoon.git`

In this tutorial we will answer the question: 'Why should you care about Python?'

* Installing things

We will be installing *python* and *jupyter-notebook*
  * Linux
  
  Depending on your favorite distro run on the terminal 
  
  ```bash 
  sudo [apt install / yum install / pacman -S ] 
  python3 python3-pip 
  ```
  This will install both the python interpreter and pip, which is a
  usefull package manager for python libraries. After this install
  jupyter-notebook, and a couple of python libraries
  
  ```bash
  sudo pip3 install jupyter numpy scipy pandas
  ```
  
  * Mac OS
  
  Install Homebrew (https://brew.sh/) from the terminal:
  ```bash
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ``` 
  Install Python (pip should be installed automatically):
  
  ```bash
  brew install python3
  python3 -m pip install jupyter numpy scipy pandas
  ```
  
  * Windows
  
  Bash shell command-line tool (useful to work with version control):
  
   - Install [bash shell](https://www.youtube.com/watch?v=Cvrqmq9A3tA&t=24s)
     1) Settings -> For Developers -> Activate Developer Mode
     2) Control Panel -> Programs -> Turn Windows Features On and Off -> Activate Windows Subsystem for Linux 
     3) Reboot
     4) Open Microsoft Store -> Search Ubuntu -> Install Ubuntu Canonical Group -> Click Launch
     5) Give Username and Password
   - run bash.exe
   - Install git `sudo apt install git` 
   - Follow Linux instructions (if installation of jupyter fails you may need to `sudo pip3 install --upgrade setuptools`)

  or download [Anaconda](https://www.anaconda.com/distribution/) (simpler way if you don't want to deal with the terminal)
