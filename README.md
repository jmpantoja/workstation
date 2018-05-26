# workstation
utilidades para instalar y configurar el software del equipo local

```bash
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```bash


añadir esto a  /etc/ansible/hosts

localhost ansible_connection=local
