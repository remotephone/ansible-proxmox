﻿# ansible-proxmox

~~~
apt update
apt install git ansible
echo "[proxmox]" >> /etc/ansible/hosts
echo "localhost ansible_host=127.0.0.1 ansible_user=root" >> /etc/ansible/hosts
ansible-playbook main.yml
~~~