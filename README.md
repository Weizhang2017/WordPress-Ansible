# Install WordPress on LEMP with Ansible

## Requirements: 

> If you have not installed LEMP, please refer to [LEMP-Ansible](https://github.com/Weizhang2017/LEMP-Ansible) to install LEMP

> Install Ansible ```sudo apt-get ansible```

> Specify the IP address and domain where you want to install WordPress as well as the ssh private key path in the hosts file

> Change the default password for Mysql in the ansbile script WordPress.yml

## Run the script 
> ```ansible-playbook WordPress.yml```