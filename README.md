# API-Desafio

[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=coverage)](https://sonarcloud.io/component_measures?id=AntonioSgarbi_desafio-api-GFT&metric=coverage)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=ncloc)](https://sonarcloud.io/dashboard?id=AntonioSgarbi_desafio-api-GFT)
[<img src="https://img.shields.io/badge/dockerhub-image-success.svg?logo=docker">](https://hub.docker.com/r/antoniosk/desafio-api)

[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=AntonioSgarbi_desafio-api-GFT)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=AntonioSgarbi_desafio-api-GFT)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=AntonioSgarbi_desafio-api-GFT)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=AntonioSgarbi_desafio-api-GFT)
[![Sqale_Index](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=AntonioSgarbi_desafio-api-GFT)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=AntonioSgarbi_desafio-api-GFT)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=bugs)](https://sonarcloud.io/summary/new_code?id=AntonioSgarbi_desafio-api-GFT)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=AntonioSgarbi_desafio-api-GFT&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=AntonioSgarbi_desafio-api-GFT)

## Descri????o

### Middleware para consumo de not??cias. 

## Proposta
```
Neste desafio voc?? ir?? desenvolver um middleware para usu??rios consumirem
not??cias de forma r??pida e pr??tica atrav??s do consumo da API de Not??cias
Gratuitas (https://apinoticias.tedk.com.br/).

O sistema dever?? conter endpoints para as seguintes funcionalidades:

- Cadastro de administrador (somente adm)
- Cadastro de usu??rio (somente adm)
- Cadastro de etiqueta para usu??rio (somente usu??rio)
- Hist??rico de par??metros acessados (acessado por adm e o pr??prio usu??rio)
- Hist??rico de etiquetas mais acessadas (somente adm)
- Acesso ??s not??cias com as etiquetas cadastradas (para o usu??rio. Caso
  n??o haja etiqueta cadastrada, dever?? retornar um erro com a descri????o
  correspondente)
- Popular banco

Exceeds:
- Testes unit??rios
- JWT e/ou Refresh Token
- Swagger ou Projeto no Postman ou OpenAPI
- Endpoint para envio de e-mail com not??cias da data corrente para
  usu??rios de acordo com suas etiquetas (somente adm)
- Envio de e-mail para usu??rio cadastrado no sistema no ato do cadastro 
```

## Sobre

### Este projeto implementa todas as Funcionalidades e Exceeds propostos 

## Play

```
docker-compose up
```
#### (consumo preparado via Swagger no caminho '/swagger-ui/index.html')
