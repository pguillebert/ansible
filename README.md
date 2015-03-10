Ansible Custom edition
======================

## Changes from Ansible 1.8.4

Changes to env-setup to allow sourcing from dash

    * 09e556e - Get rid of bash compound command to make more portable (Toshio Kuratomi)
    * 245f934 - Remove shebang and execute perms for env-setup since it must be sourced (Toshio Kuratomi)
    * b688570 - Corrected quoting of parameter expansions in hacking/env-setup (Marco Ippolito)
    * b892170 - Prefer modern-style Bash command substitution in hacking/env-setup (Marco Ippolito)
    * bee7506 - Teach env-setup how to create egg-info for ansible so that pkg_resources works (Toshio Kuratomi)

Changes to core modules :

    * a9d3fa2 - Ability to specify new SSD EBS option (Philip Misiowiec)
