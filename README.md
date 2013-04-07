cakeStrap on OpenShift
======================


Easily deploy cakeStrap (CakePHP + Twitter Bootstrap) on OpenShift



Steps-To-Deploy:
===============
coming soon...











NOTES:
======

GIT_ROOT/.openshift/action_hooks/deploy:
    This script is executed with every 'git push'.  Feel free to modify this script
    to learn how to use it to your advantage.  By default, this script will create
    the database tables that this example uses.

    If you need to modify the schema, you could create a file 
    GIT_ROOT/.openshift/action_hooks/alter.sql and then use
    GIT_ROOT/.openshift/action_hooks/deploy to execute that script (make sure to
    back up your application + database w/ 'rhc app snapshot save'first :) )

CakePHP Security:
    If you're doing more than just 'playing' be sure to edit app/config/core.php
    and modify Security.salt and Security.cipherSeed.
