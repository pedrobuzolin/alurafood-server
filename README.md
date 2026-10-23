# AluraFood Server — Eureka

Servidor de descoberta de serviços desenvolvido com **Java, Spring Boot e Netflix Eureka**, como parte do projeto AluraFood, voltado ao estudo de arquitetura de microsserviços.

## Objetivo

Centralizar o registro e a descoberta dos microsserviços da aplicação, permitindo que serviços registrados sejam localizados dinamicamente, sem depender exclusivamente de endereços fixos.

## Tecnologias

- Java 17
- Spring Boot 2.7.9
- Spring Cloud 2021.0.5
- Netflix Eureka Server
- Maven

## Como executar

**Pré-requisitos:** Java 17 e Maven, ou o Maven Wrapper incluído no projeto.

Clone o repositório:

```bash
git clone https://github.com/pedrobuzolin/alurafood-server.git
cd alurafood-server
```

Execute a aplicação no Windows:

```bash
mvnw.cmd spring-boot:run
```

No Linux ou macOS:

```bash
./mvnw spring-boot:run
```

Após iniciar o servidor, acesse o dashboard do Eureka pelo endereço configurado em `application.properties`.

> A porta utilizada depende da configuração da aplicação. Em um ambiente local, confirme o valor de `server.port` antes de acessar o dashboard.

## Conceitos explorados

- Service Discovery com Netflix Eureka.
- Registro e localização dinâmica de microsserviços.
- Integração com o ecossistema Spring Cloud.
- Organização de infraestrutura para aplicações distribuídas.
