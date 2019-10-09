Role Name
=========
Sets up the system module for metricbeat.  Uses `hmschreck.metricbeat` to
set up metricbeat.
Role Variables
--------------
```
mb_base_period: 10s
mb_cpu: true
mb_load: true
mb_memory: true
mb_network: true
mb_process: true
mb_process_summary: true
mb_socket_summary: true
mb_entropy: false
mb_core: false
mb_diskio: false
mb_socket: false
mb_top_cpu: 5
mb_top_memory: 5
mb_disk_period: 1m
mb_socket_period: 10s
```

Dependencies
------------
`hmschreck.metricbeat`

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
