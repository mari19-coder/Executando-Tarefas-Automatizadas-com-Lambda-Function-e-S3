# Executando-Tarefas-Automatizadas-com-Lambda-Function-e-S3

## 🚀 Automatização com Amazon S3 e Lambda – Visão Geral

A integração entre o Amazon S3 (Simple Storage Service) e o AWS Lambda permite criar fluxos de trabalho automatizados e sem servidor (serverless). A ideia central é simples: quando um evento acontece no S3 — como o upload de um arquivo — ele pode acionar automaticamente uma função Lambda para executar uma tarefa específica, sem necessidade de servidores dedicados.

### 🔧 Como funciona na prática:

Um arquivo é enviado para um bucket do S3.

Esse evento dispara uma função Lambda.

A função pode processar o arquivo, extrair dados, converter formatos, registrar informações no DynamoDB, enviar notificações, entre outros.

### 💡 Vantagens:

Totalmente gerenciado e escalável.

Redução de custos com infraestrutura.

Ideal para pipelines de dados, automação de uploads, e processamento sob demanda.

