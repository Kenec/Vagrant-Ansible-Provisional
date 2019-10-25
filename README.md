# Vagrant-Ansible-Provisional
Provisioning CentOS 7 on Vagrant using Ansible Provisional

### Requirement
- [Vagrant](https://www.vagrantup.com/downloads.html)

### Setup
- Clone the repository ```git clone https://github.com/Kenec/Vagrant-Ansible-Provisional.git```
- Change to the Vagrant-Ansible-Provisional directory ``` cd Vagrant-Ansible-Provisional```
- Run and Provision Vagrant ```vagrant up --provision```
- SSH into the Vagrant box ```vagrant ssh```

To ensure that the container is running, 
- Run ```docker ps```

You should see the output of Mariadb container

### Connecting to the MariaDB using Workbench
- Hostname: 192.168.33.10
- Username: zamro
- Password: supersecretpassword
- Port: 3306

