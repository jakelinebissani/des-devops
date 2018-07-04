# desafio-devops

Instalação preparada para ambientes Ubuntu 
 - Primeiro, é necessario instalar o Ansible, seguindo os seguintes passos no link: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#latest-releases-via-apt-ubuntu
 
 - Depois, de instalado, executar os seguintes comandos no terminal, dessa forma: 
 
   sudo ansible-playbook -vv ansible-role-legada/tasks/main.yml
   ansible-playbook -vv ansible-role-legada/tasks/start.yml
   ansible-playbook -vv ansible-role-legada/tasks/create-objects.yml 
