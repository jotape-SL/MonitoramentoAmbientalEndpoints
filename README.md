# Projeto: Monitoramento Ambiental

## 1. Introdução

Este projeto tem como objetivo o desenvolvimento de uma aplicação de monitoramento ambiental que emprega uma arquitetura moderna com foco em práticas de DevOps, como integração contínua (CI) e entrega contínua (CD). Este documento detalha as etapas do pipeline de CI/CD e a estratégia de containerização utilizada no projeto, bem como sua relevância no contexto de DevOps.

## 2. Pipeline de CI/CD

A configuração do pipeline de CI/CD é realizada através do GitHub Actions, que permite a automação dos processos de build, teste e deploy. O pipeline é dividido em três etapas principais: Build, Test, e Deploy.

## 3. Estrutura do Repositório

- **`CDCI.yml`**: Arquivo de configuração do pipeline CI/CD com as etapas detalhadas acima.
- **`Dockerfile`**: Configuração da imagem Docker utilizada para containerização da aplicação.

## 4. Instruções para Execução Local

Para executar o projeto localmente:
  - **Clone o Repositório**: `git clone https://github.com/jotape-SL/MonitoramentoAmbientalEndpoints.git`
  - **Configure as Variáveis de Ambiente**: Configurar variáveis de acordo com o ambiente desejado.
  - **Execute os Contêineres**: Utilize o comando `docker-compose up` para iniciar o ambiente completo.
