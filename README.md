sevdev
======

Development Environment setup and tools

_currently only works on mac_

Manual machine installation
====
1. Install Google Chrome
 1. Install LastPass

Manual dev env installation
====
1. Install XCode from App Store
2. Install XCode Command Line tools
 1.
3. Install MacPorts
 1. 
4. Install git
 1.
5. Install wget
 1. 
6. Install SourceTree
 1. 


Setup SevDev
=====
1. sudo mkdir /sev
2. sudo chown <userId> /sev
3. sudo chgrp staff /sev
4. git clone https://github.com/SevogleAdmin/sevdev.git /sev
5. update path
 1. echo 'export PATH=/sev/bin:$PATH' >> ~/.profile
 2. open new terminal window and type _sevdev_ it should now be in the path and execute.


Automated tools
=====

* mongo
 * sevdev mongo install
 * sevdev mongo start
* solr
 * sevdev solr install
 * sevdev solr start
* git
 * sevdev git-init
  * clones all git repos
* eclipse
 * sevdev eclipse install
 * sevdev eclipse start
  * still needs gwt installed, I don't have this done yet.
