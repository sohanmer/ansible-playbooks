install-vsftpd
=========

Install and configure vsftpd with below config.\n
user: ftpusr
password: password is set as short hostname

[config]
anonymous_login=NO
local_login=YES
userlist_deny=NO 

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
Name: Sohan Mer
Email: sohan1510@gmail.com
