Setup apache and enable firewall
=========

This playbook helps to install apache2 and httpd on ubuntu and RHEL server

Pre-requisite
------------
Before running playbook user need to be setup one managed node(RHEL) and two remote nodes (RHEL and Ubuntu OS servers). Should have ssh access in between master and remote nodes.Python 3.9 and above and anible 2.15 should be installed in managed node. 

Dependencies 
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Overview of the project
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
Setup and configure the project
-------

BSD

Run the project
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
