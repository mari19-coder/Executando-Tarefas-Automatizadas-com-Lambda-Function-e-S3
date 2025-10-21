# Executando-Tarefas-Automatizadas-com-Lambda-Function-e-S3

## 🚀 Automatização com Amazon S3 e Lambda 

A integração entre o Amazon S3 (Simple Storage Service) e o AWS Lambda permite criar fluxos de trabalho automatizados e sem servidor (serverless). A ideia central é simples: quando um evento acontece no S3 — como o upload de um arquivo — ele pode acionar automaticamente uma função Lambda para executar uma tarefa específica, sem necessidade de servidores dedicados.

### 🔧 Como funciona na prática:

Um arquivo é enviado para um bucket do S3.

Esse evento dispara uma função Lambda.

A função pode processar o arquivo, extrair dados, converter formatos, registrar informações no DynamoDB, enviar notificações, entre outros.

### 💡 Vantagens:

Totalmente gerenciado e escalável.

Redução de custos com infraestrutura.

Ideal para pipelines de dados, automação de uploads, e processamento sob demanda.

## 🧠 Amazon S3

- É um serviço de armazenamento em nuvem da AWS que permite"armazenar e acessar" dados de forma segura e escalável. Ele suporta qualquer tipo de arquivo (vídeo, áudio, documentos,etc.) e é ideal para backup e armazenamento de objetos.
  
  ### 💡 Princincipais vantagens do S3:
  
  -*Durabilidade:* Altamente confiável, com redundância para proteger contra falhas.
  
  -*Disponibilidade:* Garante acesso contínuo aos dados.
  
  -*Escalabilidade:* Ajusta automaticamente a capacidade de armazenamento conforme a necessidade.
  
  -*Segurança:* Oferece criptografia, controle de acesso e monitoramento de atividades.

  ## 🧠 AWS Lambda
  
  - É um serviço de computação em serveless que permite executar código em resposta a eventos, sem a necessidade de gerenciar servidores. Basta fazer o upload do código e o Lambda se encarrega de executar automaticamente, escalando conforme a demanda.

    ### 💡 Princincipais vantagens do Lambda:
    
    -*Execução sob demanda:* O código é executado apenas quando necessário, respondendo a eventos.
    
    -*Escalabilidade automática:* Ajusta a capacidade automaticamente com base no número de eventos.
    
    -*Custo Eficiente:* Cobra apenas pelo tempo de execução e pela quantidade de solicitações.
    
    -*Integração com outros serviços AWS:* Funciona como um conector entre diversos serviços da AWS, como S3, DynamoDB, API Gateway.

    

    
    


