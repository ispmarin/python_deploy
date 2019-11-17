# Python Compilation from Source

Ansible playbook to install required dependencies on Debian, clone the Python repository and compile it with the common Debian flags.

Run this playbook with

```
ansible-playbook -i hosts python_deploy.yml
```