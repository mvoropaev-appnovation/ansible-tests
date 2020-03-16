# Ansible Tests

## File index:

* [inventory.yml](inventory.yml) - list of target hosts
* [install.snmp.yml](install.snmp.yml) - a playbook to install SNMP agents on target hosts
* [restart.snmp.yml](restart.snmp.yml) - a playbook to restart SNMP agents on target hosts 
* [collect.snmp.yml](collect.snmp.yml) - a playbook to collec SNMP data from target hosts
* [reboot.yml](reboot.yml) - a playbook to reboot targets

## Execution
`ansible-playbook -v -i ./inventory.yml <Playbook>>.yml `