![Ansible Lint](https://github.com/johanneskastl/ansible-role-install_one_or_more_packages/workflows/Ansible%20Lint/badge.svg)

install_one_or_more_packages
=========

Install one or more packages, handed over to the role by variable.

Requirements
------------

None.

Role Variables
--------------

`packages_to_be_installed`: List of packages that should be installed.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.install_one_or_more_packages'
          packages_to_be_installed:
            - 'screen'
            - 'tmux'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
