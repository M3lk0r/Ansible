# Ansible

  Projeto-Ansible/  
     |-- inventories/                (arquivo de inventário e variáveis por ambiente)  
     |-- playbooks/                  (playbooks em YAML)  
     |-- roles/                      (papéis reutilizáveis)  
     |-- group_vars/                 (variáveis específicas de grupo)  
     |-- host_vars/                  (variáveis específicas de host)  
     |-- ansible.cfg                 (arquivo de configuração)  

wsl --list --verbose
wsl --install -d Ubuntu-24.04
wsl -d Ubuntu-24.04