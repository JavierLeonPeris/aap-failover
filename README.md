# aap-failover
Repository to keep two instances in sync and swap if necessary

# Run backup 

`ansible-playbook playbooks/backup.yml -e @vars/aap_vars.yml`