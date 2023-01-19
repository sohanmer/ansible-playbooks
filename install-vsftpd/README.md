install-vsftpd
=========

Install and configure vsftpd with below config. <br />
user: ftpusr <br />
password: password is set as short hostname <br />

[config] <br />
anonymous_login=NO <br />
local_login=YES <br />
userlist_deny=NO <br />

Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - install-vsftpd

License
-------

BSD

Author Information
------------------
Name: Sohan Mer <br />
Email: sohan1510@gmail.com <br />
