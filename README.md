Webapp
======
Deploy MongoDB.

MongoDB is installed from the official MongoDB repositories. A MongoDB version can be specify in `mongodb_version`. Pymongo is also installed as a dependency using PIP.

Requirements
------------
See `meta/main.yml`.

Role Variables
--------------
Authentication is managed in a separate `admin` database. The admin user credentials are set in `mongodb_admin_user` and `mongodb_admin_pass`.

A list of users can be specified in `mongodb_users`. See `defaults/main.yml` for more details.

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
Released under the [MIT license](https://opensource.org/licenses/MIT).

Author Information
------------------
Luis Gracia while at [EMBL-EBI](http://www.ebi.ac.uk/):
- luis.gracia [at] ebi.ac.uk
- GitHub at [luisico](https://github.com/luisico)
- Galaxy at [luisico](https://galaxy.ansible.com/luisico)
