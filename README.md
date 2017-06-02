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
None.

Example Playbook
----------------
Example:
```
- hosts: servers
  roles:
  - luisico.mongodb
```

TODO
----
- Select mongodb version to install.

Licence
-------
Licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Author Information
------------------
Luis Gracia <luis.gracia@ebi.ac.uk>
