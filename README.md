Role Name
=========

This role installs Ondřej Surý's PPAs for PHP, Nginx and Apache on Ubuntu 18.04.

Support for more versions and distros will come as soon as I can test on them.

Requirements
------------

`python3-apt`/`python-apt` - Role will attempt to install `apt-transport-https` and `software-properties-common` to cover these.

Role Variables
--------------

Variable | Type | Default | Usage
--- | --- | --- | ---
`ondrej_install_php_ppa` | boolean | false | Install Ondřej's PHP repository.
`ondrej_install_nginx_ppa` | boolean | false | Install Ondřej's Nginz repository.
`ondrej_install_apache_ppa` | boolean | false | Install Ondřej's Apache repository.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

Vidur Butalia