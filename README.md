# ansible-config-apache2
Este repositório contém um playbook Ansible completo e modularizado para:

    Instalação do Apache2 e PHP

    Criação e configuração de usuário (travelgo)

    Ajuste de permissões no diretório /var/www

    Backup e substituição de arquivos de configuração do Apache

    Ativação de módulos e Virtual Hosts

    Clonagem automática de projeto (Git)

    Verificações do status do servidor web

A estrutura foi separada em roles para melhor organização, facilitando a manutenção e reutilização em diferentes ambientes.

## 🛠 Estrutura do Projeto

. ├── site.yml └── roles ├── apache │ └── tasks │ └── main.yml ├── apache_config │ ├── tasks │ │ └── main.yml │ └── handlers │ └── main.yml ├── php │ └── tasks │ └── main.yml └── user └── tasks └── main.yml


🚀 Como executar

ansible-playbook site.yml --ask-become-pass

