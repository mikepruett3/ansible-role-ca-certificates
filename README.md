Ansible Role: CA Certificate Trust Store Settings
=========

Ansible role to manage CA Certificate Trust Store on Linux Servers.

Requirements
------------

The role does not require anything to run on Ubuntu, Debian or RHEL and its derivatives.

Role Variables
--------------

Available variables are listed below, along with default values (see ```defaults/main.yml```):

``` yaml
certificate_file: mycert.pem
```

```certificate_file:``` **(Required)** The CA Certificate file to use (Base-64 Encoded PEM file).

Role variables can be stored with the ```hosts.yaml``` file, or in the main variables file.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

``` yaml
    - hosts: servers
      roles:
         - role: mikepruett3.ca-certificates
```

License
-------

MIT

Author Information
------------------

Role created by [mikepruett3](https://github.com/mikepruett3) on [Github.com](https://github.com/mikepruett3/ansible-role-ca-certificates)
