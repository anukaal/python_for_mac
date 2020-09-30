# python_for_mac
# Make Python3 as default python version in Mac *

* Python3 has been the default version since python2 has sunset from January 1, 2020.

While you install python in your machine, most likely you will get python and python3 . It may seem like troublesome if we need to specific python , one of the solution is to use alias in your shell....

# PROFILE

* vi ~/.profile

* alias pip=pip3

* alias python=python3

After you edit the file, do a source ~/.profile


# ZSH 

* vi ~/.zshrc

* alias pip=pip3

* alias python=python3

After you edit the file, do a source ~/.zshrc

# BASH 

* vi ~/.bashrc

* alias pip=pip3

* alias python=python3

After you edit the file, do a source ~/.bashrc


# Pyenv

Or you can use pyenv to manage the python version.

* brew update

* brew install pyenv






