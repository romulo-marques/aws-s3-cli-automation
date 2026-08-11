# ☁️ Projeto 03: Gerenciamento e Automação do Amazon S3 via AWS CLI

## 📌 Descrição
Este projeto demonstra a criação e manipulação de recursos no Amazon S3 utilizando a Interface de Linha de Comando (**AWS CLI**) via **AWS CloudShell**. O objetivo foi criar um bucket S3, gerar um arquivo de teste e realizar o upload via terminal.

## 🛠️ Tecnologias Utilizadas
* **Amazon S3** (Simple Storage Service)
* **AWS CLI v2**
* **AWS CloudShell / Linux Bash**

## 🚀 Passos Executados

1. **Acesso ao Terminal Executivo:**
   * Inicialização do ambiente interativo via AWS CloudShell na região `us-east-1`.

2. **Gerenciamento do S3 via CLI:**
   * Criação do bucket S3 via terminal:
     `aws s3 mb s3://portfolio-s3-rmarques --region us-east-1`
   * Criação do arquivo local e upload para a nuvem:
     `echo "Arquivo de teste para o Projeto 03" > teste.txt`
     `aws s3 cp teste.txt s3://portfolio-s3-rmarques/`
   * Listagem e verificação dos objetos armazenados no bucket:
     `aws s3 ls s3://portfolio-s3-rmarques/`

## 📊 Aprendizados
* Manipulação e armazenamento de objetos na nuvem via linha de comando.
* Automação de tarefas em nuvem utilizando comandos Shell/Bash.
* Uso produtivo do AWS CloudShell para gestão de infraestrutura.

## 📸 Evidências de Execução

### 1. Execução dos Comandos no AWS CloudShell
<img width="980" height="554" alt="image" src="https://github.com/user-attachments/assets/75a32d42-bc9a-4a69-aa3d-bbdcae9e3a64" />
<img width="988" height="549" alt="image" src="https://github.com/user-attachments/assets/33119696-c4da-4a14-9c32-990f9391ffb4" />
