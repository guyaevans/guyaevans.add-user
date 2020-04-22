Add-Users
=========

Role that adds users and ssh keys


Role Variables
--------------

Variables are stored in the variable file of your playbook

		add_user:
		 - os_user: username1
		   os_user_pw: password1
		   ssh_key_file: ssh.pub


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: guyaevans.add-users}


