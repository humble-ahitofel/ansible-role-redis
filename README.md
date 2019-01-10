redis
=========

Install and configure Redis on Debian.

Changes to Debian defaults:
- Change logging to syslog, disable logfile.
- Set vm.overcommit_memory=1.
- Raise Redis ulimit.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example
----------------
```yaml
- role: libraries-fi.redis
```

License
-------

MIT

Author Information
------------------

Libraries.fi
