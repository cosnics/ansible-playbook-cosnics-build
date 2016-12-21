Cosnics Build
==============

example: ansible-playbook build.yml --extra-vars "branch=master workspace=/home/deployer/workspace repo=https://github.com/cosnics/cosnics.git"

Build the source + install dependencies 

Playbook Variables
--------------
branch: the repo branch
workspace: where to build the source
repo: the repo url (git)

License
-------

MIT