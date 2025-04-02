## Desafio 2: AWS + Terraform

### Descrição
Neste desafio, o objetivo é realizar o processo de provisionamento de infraestrutura na AWS utilizando o **Terraform**. Será criado um **security group**, uma **EC2** e, por fim, o deploy de um site via o arquivo **script.sh**, que permitirá acessar o site pelo navegador.

### Passos principais:

- **1. Configurar a conta no provedor de nuvem (AWS)**:
  Primeiramente, é necessário criar e configurar uma conta na AWS, caso ainda não tenha.

- **2. Instalar o Terraform localmente**:
  Baixe e instale o Terraform na sua máquina local.

- **3. Instalar o AWS CLI**:
  Instale o AWS CLI para permitir a comunicação entre o Terraform e a AWS.

- **4. Adicionar o provedor AWS localmente**:
  No arquivo de configuração do Terraform, adicione as credenciais do provedor AWS.

- **5. Escrever os arquivos de configuração**:
  Utilize a **receita de bolo** disponibilizada no repositório do GitHub ou baixe os arquivos de configuração do repositório no Discord.

  - **6. Inicializar o Terraform**:
  Execute o comando abaixo para inicializar o Terraform:
  ```bash
  terraform init

- **7. Visualizar a infraestrutura a ser criada: Execute o comando de Plan para verificar o que será criado**:
  ```bash
   terraform plan

- **8. Provisionar a infraestrutura na AWS: Execute o comando apply para realizar o provisionamento na AWS**:
  ```bash
  terraform apply
  
- **9. Eliminar os recursos provisionados: Após registrar as evidências, execute o comando destroy para destruir os recursos criados**:
  ```bash
  terraform destroy 

### Tecnologias Utilizadas
- AWS: Provedor de nuvem onde a infraestrutura será criada.
- Terraform: Ferramenta de IaC (Infraestrutura como Código) para provisionamento de infraestrutura.
- AWS CLI: Ferramenta de linha de comando da AWS para gerenciar os recursos.
- script.sh: Script utilizado para o deploy do site.

### Evidência
![Imagem](https://github.com/ingridmoitinho/avanti-bootcamp-devops/blob/main/desafio-2-terraform-aws/evidencia-deploy-desafio-2.png)


