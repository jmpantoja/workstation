# workstation
utilidades para instalar y configurar el software del equipo local


## install ansible

```bash
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```


```bash
# add to /etc/ansible/hosts
localhost ansible_connection=local

```


## install workstation

1. `git clone https://github.com/jmpantoja/workstation.git .`
1. `cd workstation` 
1. `ansible-galaxy install -r ansible/requirements`
1. `sudo ansible-playbook ansible/playbook.yml --connection=local`
