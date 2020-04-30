docker
=========

Installs docker and configures useful systemd units for managing containers

Requirements
------------

The docker apt repo configured on the target machine. See [my
role](https://github.com/ThreeFx/ansible-apt) for more info.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: docker

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
