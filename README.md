ansiFilebeat
=========

Ansible role to install Filebeat

Requirements
------------

python >= 3.8
Ansible

Role Variables
--------------

Supported variables are as follows:

beat_version: Beat version. Default is 7.x
beat_package_version- Beat package version. Default is 7.x


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansiFilebeat

License
-------

BSD
