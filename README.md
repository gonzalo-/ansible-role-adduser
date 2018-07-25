Ansible Role Adduser for OpenBSD
================================

Create users, the .pub key and put them on doas.conf

Example Playbook
----------------

     ---
     - hosts: all
       roles:
       - role: gonzalo-.adduser

       become: True
       become_method: doas

       vars:
           username: pepe
           password: HoLa.321

License
-------

BSD
