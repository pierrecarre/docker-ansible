## Ansible with CentOS 7

This is docker images of CentOS 7 with several versions of Ansible.

## Loading different versions of Ansible

The different versions are defined using TAGs.

The available versions are

* 2, 2.0, 2.0.0-0.6.rc1 - Ansible 2.0
* latest, 1, 1.9, 1.9.4 - Ansible 1.9
* 1.8, 1.8.4 - Ansible 1.8

Example to run a container with Ansible 2

    docker run -ti pierrecarre/ansible:2
