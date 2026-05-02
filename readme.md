# Spring Proxy Lab

Projeto simples para estudar Reverse Proxy com Apache 2.4 na frente da uma aplicação Spring Boot

## Arquitetura

Cliente -> Apache -> Spring Boot (Tomcat)

- Apache expõe porta 80
- Spring Boot roda internamente na porta 8080
- Apache encaminha `/api/*` para o backend

## Endpoint

``http://localhost/api/v1/say-hello``


## Tecnologias

- Java 21
- Spring Boot
- Apache HTTP Server 2.4
- Docker 
- Docker compose

## Subir Projeto

``docker compose up --build``

