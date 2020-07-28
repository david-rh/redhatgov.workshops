This is the setup playbooks for the Developer Journey, from basic containers to OpenShift


Prerequisites
  * Ansible
  * Python
  * Python modules boto boto3 kubernetes openshift
      pip install boto boto3 kubernetes openshift
  * Ansible openshift_gogs
      ansible-galaxy install siamaksade.openshift_gogs

To install first copy group_vars/all/vars.yml.template to group_vars/all/vars.yml
<TODO> Convert to vault

Obtain pull Secret from https://cloud.redhat.com/openshift/install/pull-secret

Edit vars.yml and set values as appropriate

Now run

ansible-playbook -vvv workshop-setup.yml

