# Linux
## Overview
**Linux** is a collection of Ansible playbooks and Bash scripts designed to automate the process of hardening a system to **STIG (Security Technical Implementation Guide) standards**.

## Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/Linux.git
cd Linux
```
ensure ansible is installed
```bash
sudo apt install ansible  # Debian-based
sudo yum install ansible  # RHEL-based
```
if running this locally on a system:
```bash
sudo bash enfoce.sh
```
if running on ansible controller:
```bash
ansible-playbook site.yml -b
```

