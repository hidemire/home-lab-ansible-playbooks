# Home Lab Asnible Playbooks

```bash
ansible all -i inventory/test/hosts.ini -m ping -u root
ansible-playbook -l all -i inventory/test/hosts.ini -u root setup_ubuntu2004/playbook.yml
```
