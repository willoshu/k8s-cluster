K8s-cluster
=========

This role deploy a kubernetes cluster

Requirements
------------

This role requires the installation of installation of ansible.posix collection in addition to ansible-core
ansible-galaxy collection install ansible.posix

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None so far

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: control:workers
      roles:
         - k8s_cluster

Note: Inventory file must contain the following groups: 'control' and 'workers'

License
-------

0BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
