Purpose
=======

Spin up vagrant nodes based on nodes.yml definitions
Provisions nodes by bootstrapping using Ansible
````
ansible/bootstrap.yml
````
Installs Ansible on nodes during bootstrap
updates host_vars to allow provisioning nodes within Vagrant nodes using Ansible as well
