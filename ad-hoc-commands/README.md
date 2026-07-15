# Project 02 - Ansible Ad-hoc Commands

## Objective
Learn how to execute one-time administrative tasks on remote servers using Ansible ad-hoc commands.

## Environment
- Control Node: Ubuntu 24.04 (AWS EC2)
- Managed Node: Ubuntu 24.04 (AWS EC2)
- Ansible Version: 2.20.1

## Commands Executed

### Check Hostname

```bash
ansible all -m command -a "hostname"
```

### Check Uptime

```bash
ansible all -m command -a "uptime"
```

### Check Disk Usage

```bash
ansible all -m command -a "df -h"
```

### Check Memory

```bash
ansible all -m command -a "free -m"
```

### Check OS Information

```bash
ansible all -m command -a "cat /etc/os-release"
```

### Check Kernel Version

```bash
ansible all -m command -a "uname -r"
```

### Gather Ansible Facts

```bash
ansible all -m setup
```

## Key Learnings

- Used the `command` module to execute commands remotely.
- Gathered system information using the `setup` module.
- Understood the difference between `command` and `shell` modules.
- Successfully managed a remote EC2 instance using Ansible.

