Wordlists
=========

An opinionated collection of wordlists for fuzzing and cracking.

Requirements
------------

Requires curl or wget for downloads.

Role Variables
--------------

wordlist_path = '~/Wordlists'

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: leesoh.wordlists }

License
-------

BSD

