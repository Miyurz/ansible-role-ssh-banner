Role Name
=========

This role could be used while bootstrapping nodes on cloud or on your VM to echo/display the hostname along with any relevant details like privacy policy etc.

Requirements
------------


Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
You could pass a parameter to the role like below:

roles:
  - {role: ssh-banner, host: 'My Machine' ,tags: ['ssh-banner', 'banner', 'bootstrap', 'provision']}

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
