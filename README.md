# logrotate

Forked version of logrotate with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/logrotate.git
* cd logrotate
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/logrotate.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
