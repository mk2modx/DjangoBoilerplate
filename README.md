## Basic Django setup

installing python3 and setting up pip3 on Centos 8
this installs python 3 and pip  / type python3 or pip3 when system-wide

$ sudo dnf install python3

install python and pip tools for using virtualenv

$ sudo yum install python3-devel
$ sudo yum groupinstall 'development tools'
$ sudo pip3 install virtualenv

create env and activate

$ python -m venv env
$ source env/bin/activate

** followed these two tutorials for the implementation of django debug toolbar

https://www.youtube.com/watch?v=GEogao-tUec&list=PLLRM7ROnmA9FgFlqn-HHBz0LJ62qJBwSw

https://django-debug-toolbar.readthedocs.io/en/latest/configuration.html
