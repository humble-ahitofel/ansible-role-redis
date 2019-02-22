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

* redis_save list of save options. Can be set to empty list to disable rdb.
* redis_maxmemory set maxmemory.
* redis_maxmemory_policy set maxmemory-policy.

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
