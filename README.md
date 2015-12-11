Role Name
=========

Role sets up monit to manage nginx-based php-fpm installation. It also sets up monit web interface on 127.0.0.1:2812.

Requirements
------------

nginx
php-fpm

Role Variables
--------------

- monit_php_fpm_emails
- monit_php_fpm_url


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: web_servers
  roles:
     - { role: monit-php-fpm, monit_php_fpm_url: "http://127.0.0.1/ping.php" }
```

License
-------

BSD

Author Information
------------------

© GitInSky