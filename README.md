# vagrant-ansible-phpstarter
1. Install vagrant and ansible in your system
2. Clone this repo into the wished folder (e.g. ~/Dev/mysuperproj)
3. Go to the proj folder and type: vagrant up
4. Change the path of private key file. Modify the ansible_ssh_private_key_file variable value (located at group_vars/webservers) to your case.
5. And again in the proj folder type: ansible-playbook playbook-phpstarter
6. Cool. The address of the guest machine is 192.168.10.10 (bridge mode). The src directory is for your proj files
