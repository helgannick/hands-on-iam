
# 🚀 Projeto Cloud - Automação de Criação de Usuários IAM na AWS

[![AWS](https://img.shields.io/badge/AWS-Cloud-orange)](https://aws.amazon.com/)
[![Shell Script](https://img.shields.io/badge/Shell%20Script-Automation-blue)](https://www.gnu.org/software/bash/)
[![Status](https://img.shields.io/badge/Status-Concluído-green)]()

---

## 📄 Descrição do Projeto

Este projeto foi desenvolvido para automatizar a criação de usuários IAM (Identity and Access Management) na Amazon AWS, a partir de usuários locais (on-premises).  
Utilizando **Shell Script** e **AWS CLI**, o processo inclui a criação de usuários, definição de políticas, organização em grupos e configuração de MFA (autenticação multifator), tudo de forma segura e eficiente.

---

## 🛠️ Tecnologias e Serviços Utilizados

![Organização de Projeto Cloud](./docs/organizacao_projeto_cloud.png)

- **Amazon AWS** como provedor de serviços Cloud
- **AWS IAM** para gestão de identidades e acessos
- **AWS CLI** para interação com a AWS via terminal
- **Shell Script** para automação de processos
- **Git Bash** para execução dos scripts no ambiente local

---

## 🖥️ Arquitetura do Projeto

![Automating User Creation in AWS](./docs/automating_user_creation_in_aws.png)

O fluxo funciona da seguinte maneira:
- Captura de informações dos usuários locais
- Criação de usuários na AWS IAM
- Definição de políticas de acesso apropriadas
- Adição dos usuários a grupos predefinidos
- Configuração obrigatória de MFA para segurança

---

## 📂 Organização do Projeto

Estrutura de diretórios:

- **scripts/**: Contém os scripts de automação.
- **docs/**: Documentação e imagens utilizadas.
- **README.md**: Este arquivo de documentação.

---

## ⚙️ Funcionamento

![Automatizando Criação de Usuários](./docs/create-users.png)
![Automatizando Listando os Usuários](./docs/list-users.png)
![Automatizando Console AWS](./docs/console-aws.png)



O script realiza:
- Leitura dos usuários de um arquivo `.csv` ou entrada manual
- Criação de usuários no IAM com configuração inicial
- Atribuição de políticas customizadas
- Ativação da autenticação multifator (MFA)

