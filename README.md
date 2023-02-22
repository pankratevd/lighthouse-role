Lighthouse
=========

This role can install NGINX with Lighthouse on EL

Role Variables
--------------
|vars|description|
|----|-----|
|lighthouse_location_dir|path to location lighthouse files|
|nginx_user|user's name for nginx|
|nginx_port|port that uses nginx|


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role:  lighthouse}

License
-------

MIT

Author Information
------------------

Dmitrii Pankratev