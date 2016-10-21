linuxmuster-client-auth
-----------------------

This package enables an ubuntu client to auth against an ldap server
on the linuxmuster Server

  * The ldap users "pgmadmin" and "administrator" have
    administrative rights via sudo
  * Homedirs of ldap users ar created on the fly via pam_mkuserdir.so
    from /etc/skel
  * This package has no profile managing capabilities

Tested on

  * Ubuntu 16.04 Xenial Xerus Alpha2 
 
 Attention:
  * requires systemd so it is incompatible with Ubuntu < 15.04 
  * only compatible with lightdm/mdm displaymanager

Remarks:
 * should now also work stable in an subnetting environment 
