# API Serverless na AWS

## Objetivo
Expor métricas do pipeline ETL via endpoint REST com custo mínimo.

## Arquitetura
![arquitetura](docs/arch.png)

## Stack
- API Gateway
- AWS Lambda (Python)
- DynamoDB
- CloudWatch (logs)

## O que foi feito
- Criação de função Lambda stateless
- Endpoint REST com API Gateway
- Armazenamento no DynamoDB
- Logs estruturados no CloudWatch

## Evidências
- diagrama: `docs/arch.png`
- logs: `docs/cloudwatch.png`

## Próximos passos
- autenticação simples via API Key
- paginação de consultas

## Licença
MIT
