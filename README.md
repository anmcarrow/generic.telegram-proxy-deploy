
generic.telegram-proxy-deploy

=========

Ansible-role for deploy dockerized 3proxy Soxks-proxy server for
use with Telegram Messenger.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: all
  roles:
    - generic.telegram-proxy-deploy
```

License
-------

MIT

Author Information
------------------

Andrey Makarov <mb@mcrrw.me>
