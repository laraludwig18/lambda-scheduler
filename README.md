# Lambda Scheduler

Função que executa a cada minuto uma requisição para a url http://whatthecommit.com/ e salva no DynamoDB a resposta, feita para treinar conceitos de serverless.

## Inicialização

Instalar dependências:
```
yarn
```
Instalar serverless framework:
```
yarn global add serverless
```

## Comandos

Rodar função local:
```
yarn invoke-local
```
Rodar função no AWS Lambda:
```
yarn invoke
```
Realizar deploy:
```
sls deploy
```