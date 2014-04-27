Dovecot
========

Install and configure the Dovecot MTA to interface with Maildir/ style user mail stores.

Requirements
------------

An SMTP daemon, like `postfix` on a RedHat flavored system.

Role Variables
--------------


Dependencies
------------


Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: dovecot }

License
-------

MIT
