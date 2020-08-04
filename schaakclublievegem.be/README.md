# ansible-wsv
ansible config wsv web server

## how to run:

ansible-vault create group_vars/db/vault.yml

....
---
vault_mysql_password=BLAHBLAHBLAHBLAH
....

ansible-playbook play.yml -u vincent -Kb --ask-vault-pass
BECOME PASSWORD: ...
Vault Password: ...
