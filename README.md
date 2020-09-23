cloud3rsio.set_alternative_python_path
=========

Set alternative python path.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.set_alternative_python_path
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `set_alternative_python_path.python_path` | `/usr/bin/python3` | String |

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.set_alternative_python_path
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
