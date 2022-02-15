# Roles Name: MariaDB-Galera , Maxscale , keepalive

Two Ansible Roles that install MariaDB-Galera and Maxscale with keepalive on Ubuntu 20.04 LTS.



## Requirements

```
You need to add ip and names in /etc/hosts and change the variables for yourself.

vim /etc/hosts

192.168.56.103    db1

192.168.56.104    db2

192.168.56.105    db3

192.168.56.101   maxscale1

192.168.56.102   maxscale2 
```



## Dependencies

None.



## Execute Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
ansible-playbook -i ./inventory ./install.yml
```



## Author Information

Akbar Mohammadi