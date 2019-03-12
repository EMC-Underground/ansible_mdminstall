### Copy vars.yml to:
roles/all/vars/vars.yml

### Update Hosts file with Server IP addresses

### Run Playbook
```shell
ansible-galaxy install ericsysmin.chrony
ansible-playbook playbook.yml -u <user> -i hosts

```
