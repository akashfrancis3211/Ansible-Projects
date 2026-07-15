# Project 01 - Ansible Ping Test

## Objective
Verify connectivity between the Ansible Control Node and Managed Node using the Ansible ping module.

## Technologies
- Ubuntu 24.04
- AWS EC2
- Ansible
- SSH

## Commands Used

ansible all -m ping

ansible all -m setup

ansible all -a "hostname"

ansible all -a "uptime"

ansible all -b -a "whoami"

## Result

Successfully established communication between the control node and managed node and executed ad-hoc commands.
