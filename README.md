icinga2-client-setup
=========
To install icnga2 client and setup the client node to send/recieve api connection in Redhat/Centos 6 & 7 servers.
Please test in on test environment before doing it on production servers.

Role Variables
--------------

In defaults/main.yml add the salt_key from the icinga master , also enter the icinga master hostname and ip address
In 

------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }


eg:- install.yml
     - name: message
       hosts: server
       tasks:
       - include_role:
             name: icinga2-client-setup

     ansible-playbook install.yml 


License
-------

Apache

Author Information
------------------



# ansible-role-icinga2-client-setup
