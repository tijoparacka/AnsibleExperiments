
This is a work in progress.

* VMs require access to the internet.
* The latest two versions of Oracle's JDK will be downloaded to /tmp/ and version 8u161 will be installed.

For setting up kerberos Server
ansible-playbook -i ../hosts.ini -u ec2-user  --private-key ~/Documents/tt_NV.key kdc_server.yaml

For setting up kerberos client
ansible-playbook -i ../hosts.ini -u ec2-user  --private-key ~/Documents/tt_NV.key kdc_client.yaml

*
# AnsibleExperiments
# AnsibleExperiments
