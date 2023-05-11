Role Name
=========
draxalene.letsencrypt

draxalene role for ansible to deploy Let's Encrypt certbot tool. (by hopla.cloud)

Requirements
------------

None.

Role Variables
--------------

Select web server type (apache or nginx).
This is set as fact variable by hoplacloud.apache_php or hoplacloud.nginx_php
server_type: "apache"

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      server_type: "apache"
      roles:
         - draxalene.letsencrypt

License
-------

GPLv3

Author Information
------------------

Alexandre MOREAU by hopla.cloud
