
# Ansible Docker Automation Project

## 🔧 Overview
This project automates Docker installation and container deployment using Ansible.

## 📁 Files
- `inventory.ini`: Target hosts
- `playbook.yml`: Main playbook
- `roles/docker/tasks/main.yml`: Task to install Docker & deploy NGINX

## 🚀 How to Run
```bash
ansible-playbook -i inventory.ini playbook.yml
```

This installs Docker and runs an NGINX container accessible on port 8080.
