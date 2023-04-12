letsencryptssl
=========

Sets up certbot and creates a certificate for a domain.

Requirements
------------

The `snap` community role is required:

```shell
ansible-galaxy collection install community.general
```

Role Variables
--------------

Parameters:

- `email`: Email address to use for the certificate.
- `domain`: Domain to create a certificate for.


Dependencies
------------

- `community.general`
  - `community.general.snap`

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

Rudolf Olah
