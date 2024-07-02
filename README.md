# HEXAGONAL ARCHITECTURE

## Visão Geral

Este projeto implementa a arquitetura hexagonal para um sistema de gerenciamento chamado Gerenciamento XPTO. 
A arquitetura hexagonal é uma abordagem de design de software que visa criar aplicações altamente desacopladas, permitindo que os componentes internos do sistema sejam independentes das suas interfaces externas.

## Estrutura do Projeto

* API: Contém os controladores e a configuração da API.
* Applicantion.Tests: Testes de unidade e de integração para a camada de aplicação.
* Application: Contém a lógica de negócio e serviços do aplicativo.
* Domain.Tests: Testes de unidade para a camada de domínio.
* Domain: Contém as entidades e regras de negócio do domínio.
* Infra.Tests: Testes de unidade para a camada de infraestrutura.
* Infra: Implementações de repositórios, contexto de banco de dados e outros serviços de infraestrutura.
* WebApplication1: Projeto da aplicação web.

## Configuração do Ambiente

* dotnet restore
* dotnet build

## Para testar 

* dotnet test
