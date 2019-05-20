# This is didactic-bassoon

git clone git@github.com:lardellin/didactic-bassoon.git

In this tutorial we will answer the question: 'Why should you care about Python?'

* Installing things
We will be installing *python* and *jupyter-notebook*
  * Linux
  
  Depending on your favorite distro run
  
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
  
  Install Homebrew (https://brew.sh/): 
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

```brew install python 
python -m pip install jupyter numpy scipy pandas
```
  * Windows
  
  Bash shell command-line tool (useful to deal with version control):
   - Install [bash shell](https://www.youtube.com/watch?v=Cvrqmq9A3tA&t=24s)
   - run bash.exe
   - Follow Linux instructions 

  or download [Anaconda](https://www.anaconda.com/distribution/)
