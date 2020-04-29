
## Ansible cluster commands

ansible all -i ./hosts/cluster-hosts.ini -u centos --private-key key.pem -m shell -a "ls -l /opt/" 
