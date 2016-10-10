Author: Solomon Zook

The application will transmit a formatted schedule built from schedule.txt, found in the data folder
* It shows the week number, start date, and some information about each week
* The current week is highlighted

## To Use

* Clone in your workspace from github, git clone https://github.com/solzook/proj2-flask
* 'bash ./configure' should create appropriate configuration files on most Unix files.   
  * If you are using Windows, some additional editing of configuration files may be necessary.  
* You might have to edit the Makefile to find the right version of pyvenv.

* If you can run flask applications in your development environment, the application might be run by
`   python3 syllabus.py`
and then reached with url
`   http://localhost:5000`

`make run` will launch the debugging server built into flask.  It
provides the best support for tracking down bugs in your server, but
it's not suitable for use by many users or over a long period.  `make
service` starts a Green Unicorn (gunicorn) server; you may note the extra
lime sparkles all around you.  Green Unicorn can be used for servers
that run over a longer period (e.g., if you want to leave a web
service running on your Pi).   

