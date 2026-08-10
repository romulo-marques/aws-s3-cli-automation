# ☁️ Projeto 01: Automação e Gerenciamento do Amazon S3 via AWS CLI

## 📌 Descrição
Este projeto demonstra a configuração, autenticação e manipulação de recursos na nuvem AWS utilizando a linha de comando (**AWS CLI**) e o **Git Bash**. O objetivo foi criar um bucket S3 e realizar o upload de arquivos via terminal sem a necessidade da interface gráfica.

## 🛠️ Tecnologias Utilizadas
* **AWS S3** (Simple Storage Service)
* **AWS IAM** (Identity and Access Management)
* **AWS CLI v2**
* **Git Bash / Shell Script**

## 🚀 Passos Executados

1. **Configuração de Segurança e IAM:**
   * Criação do usuário programático `admin-cli` no IAM.
   * Geração e configuração segura das chaves de acesso (`Access Key` e `Secret Key`).

2. **Autenticação via Terminal:**
   * Configuração das credenciais locais usando o comando `aws configure` na região `us-east-1`.
   * Validação de identidade via `aws sts get-caller-identity`.

3. **Gerenciamento do S3 via CLI:**
   * Criado o bucket S3 via terminal:
     `aws s3 mb s3://meu-portfolio-aws-rmarques-2026`
   * Upload de arquivos realizado com sucesso:
     `aws s3 cp arquivo_teste.txt s3://meu-portfolio-aws-rmarques-2026/`
   * Listagem e verificação dos objetos no bucket:
     `aws s3 ls s3://meu-portfolio-aws-rmarques-2026/`

## 📊 Aprendizados
* Prática de gerenciamento de identidades e acessos na AWS (IAM).
* Automação de tarefas em nuvem utilizando Shell/Bash.
* Boas práticas de segurança (armazenamento seguro de credenciais).
