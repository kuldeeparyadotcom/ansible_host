# ansible_controller
Ansible controller node - Vagrant based environment

Quick steps to get up
1. Clone repo
2. vagrant up
3. update /etc/ansible/host
4. Add private key file with 400 permission
5. Run Add Hoc Commands like ansible all -m ping -u docker --private-key docker.pem
Or Run playbooks
