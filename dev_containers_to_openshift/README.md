This is the setup playbooks for the Developer Journey, from basic containers to OpenShift


Prerequisites
  * Ansible
  * Python
  * Python modules boto boto3
      pip install boto boto3


To install first copy group_vars/all/vars.yml.template to group_vars/all/vars.yml
<TODO> Convert to vault

Edit vars.yml and set values as appropriate

Now run

ansible-playbook -vvv workshop-setup.yml

