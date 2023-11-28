vector-role
=========

Install vector on centos 7-8

Role Variables
--------------

| vars | description |
|------|----------|
| vector_version | Versions of Vector to install|
| vector_config_dir | directory for configfile Vector |
| vector_ip | ip-adresses on endpoint url Vector |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector-role }

License
-------

MIT

Author Information
------------------

Ivan Malysehev
