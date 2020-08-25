# ansible-workshop-compliance-remediation
Simple playbook to remediate security compliance configuration on linux hosts

This playbook does 2 things:

 - Checks to see if the gpg check flag is set in /etc/yum.conf

 - If the playbook is run in check mode and the above check of yum.conf shows non-compliance then the playbook will submit an incident with a ServiceNow system

