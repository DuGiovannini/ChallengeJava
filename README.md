# ChallengeJava

## Descrição do Projeto

Este projeto consiste em uma API RESTful desenvolvida em Java utilizando Spring Boot, com o objetivo de suportar a solução do desafio da empresa Mottu. A API gerencia motos e pátios, oferecendo operações CRUD completas para as entidades principais, além de recursos como paginação, validação de dados com Bean Validation, tratamento centralizado de erros, cache para otimização das requisições e uso de DTOs para melhor controle e segurança dos dados.

O projeto utiliza o banco de dados em memória H2 para facilitar o desenvolvimento e testes locais.

---

## Como Executar o Projeto

### Pré-requisitos

- Java JDK 17 instalado e configurado  
- Maven instalado e configurado no sistema  
- IDE ou editor de texto (recomendado VS Code com extensões Java e Spring Boot)  

## Passos para executar

```bash
git clone https://github.com/DuGiovannini/ChallengeJava.git
```

```bash
cd ChallengeJava
```

```bash
mvn spring-boot:run
```

Acesse a aplicação nos seguintes endpoints:

```
http://localhost:8080
http://localhost:8080/api/patios?page=0&size=10
http://localhost:8080/api/motos?page=0&size=10
```

---

## Integrantes

- Eduardo Ribeiro Giovannini  
- Gabriel Teodoro Gonçalves Rosa  
- Luka Ura Shibuya  

---

## Observações

- A API possui tratamento global de erros para garantir mensagens claras ao cliente.  
- Paginação e cache foram implementados para melhorar performance e escalabilidade.  
- Os dados são validados utilizando Bean Validation para garantir integridade das informações.
