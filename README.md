# ansible-lab
- create_users.yml:
       Description: Create the users in different job groups, multiple groups with different inventory groups.
       Vars_file: user_list.yml
- update_etc_hosts.yml:
       Description: Build /etc/host file for specific set of hosts with data of  all the hosts in the ansible environment.
       template_file: hosts.j2
       
