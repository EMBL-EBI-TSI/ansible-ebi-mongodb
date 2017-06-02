Webapp
======
Deploy MongoDB.

Requirements
------------
See `meta/main.yml`.

Role Variables
--------------
See `defaults/main.yml`.

Dependencies
------------
Depends on EPEL repository being present to install `python-pip` (ie role `geerlingguy.repo-epel`).

Example Playbook
----------------
Example:
```
- hosts: servers
  roles:
    - geerlingguy.repo-epel
    - mongodb
```

TODO
----
- Select mongodb version to install.

Licence
-------
Licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Author Information
------------------
Luis Gracia while at [EMBL-EBI](http://www.ebi.ac.uk/):
- luis.gracia [at] ebi.ac.uk
- GitHub at [luisico](https://github.com/luisico)
- Galaxy at [luisico](https://galaxy.ansible.com/luisico)
