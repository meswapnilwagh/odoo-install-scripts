Odoo Install Scripts
=======================

Odoo (Formely OpenERP) Install Scripts.

> Please use the master branch for install Odoo 8.0 on Ubuntu 14.04.
> Submit bug/issue reports here: https://github.com/lukebranch/odoo-install-scripts/issues

<H4>Please use the 8.0 branch:</H4> 
    sudo wget https://raw.githubusercontent.com/lukebranch/odoo-install-scripts/8.0/odoo-saas4/ubuntu-14-04/odoo_install.sh
    sudo sh odoo_install.sh
<i>This will provide you with the latest working 'stable' version of the module built for the 8.0 branch. Please be advised this module is still under development.</i>

TODO [master]
=======================
* Check dependencies against https://github.com/odoo/odoo/blob/8.0/requirements.txt and revise accordingly
* Setup UFW and fail2ban
  * create a module to work with fail2ban and ufw for blocking brute force attempts to Odoo login and other interfaces.  

TODO [dev-ngx_pagespeed-ngx_cache_purge]
=======================
>> (WIP) Finish nginx compile script to compile latest stable Nginx with ngx_pagespeed, ngx_cache_purge, and ngx_postgres

TODO [...]
=======================
>> Multi-domain, multi-instance Odoo install script branch

TODO [...]
=======================
>> Install script with docker containers

TODO [...]
=======================
>> SaaS install script

TODO [...]
=======================
>> Production ready install script?
