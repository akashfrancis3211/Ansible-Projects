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

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/789145f3-5278-42ab-9c53-1787d4a2db48" />


ansible all -a "hostname"

ansible all -a "uptime"

ansible all -b -a "whoami"

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/5ba695a1-dbd2-4592-8787-03a7fc434b17" />

## Result

Successfully established communication between the control node and managed node and executed ad-hoc commands.
