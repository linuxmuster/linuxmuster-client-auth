linuxmuster-client-auth
-----------------------

This package enables an ubuntu client to auth against an ldap server
on the "Linux Musterlösung".

* The ldap users "pgmadmin" and "administrator" have
administrative rights via sudo
* Homedirs of ldap users are created on the fly via pam_mkuserdir.so
from /etc/skel
* This package has no profile managing capabilities

Tested on

* Ubuntu 12.04LTS beta2
* Linux Mint 12 "Lisa" (based on Ubuntu 11.10)
* Linux Mint 17 "Qiana" (based on Ubuntu 14.04LTS)
