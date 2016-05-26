IBM DSA
=========

This role installs IBM DSA

Requirements
------------

None

Role Variables
--------------

* `ibm_dsa_url`: URI to download DSA from

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: kostyrevaa.ibm-dsa }

License
-------

Apache 2.0

Contributing
----------------

When sending PR make sure your changes are backward-compatible.


Author Information
------------------

Aleksandr Kostyrev
