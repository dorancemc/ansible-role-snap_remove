ansible-snaps
=============

Role to remove snapd from Ubuntu

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Requirements
--------------------

```yaml
- name: snaps
  version: 1.0.0
  src: https://github.com/dorancemc/ansible-snaps
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
      - { role: snaps }
```

Test
----

```bash
ansible-playbook -u vagrant -i 192.168.243.219, tests/test.yml --syntax-check
```

License
-------

Apache 2.0

Author Information
------------------

Dorance Martinez
