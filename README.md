# Home Lab Asnible Playbooks

```bash
cp -r inventory/sample inventory/test
ansible all -i inventory/test/hosts.ini -m ping -u root
ansible-playbook -l all -i inventory/test/hosts.ini -u root setup_ubuntu2004/playbook.yml
ansible-playbook -l all -i inventory/test/hosts.ini -u hidemire setup_docker/playbook.yml
```
