selftests
=========

This ansible role let's you test Linux kernel selftests.

Requirements
------------

You have a kdevops environment setup.

Role Variables
--------------

  * selftests_script: the selftest test script you should run
  * selftests_linux_dir: where your Linux kernel directory is

Dependencies
------------

None.

Example Playbook
----------------

Below is an example playbook task:

```
---
- hosts: all
  roles:
    - role: selftest
```

For further examples refer to one of this role's users, the
[https://github.com/mcgrof/kdevops](kdevops) project or the
[https://github.com/mcgrof/oscheck](oscheck) project from where
this code originally came from.

License
-------

GPLv2
