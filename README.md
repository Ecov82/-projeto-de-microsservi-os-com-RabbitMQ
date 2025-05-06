# Microsserviços com Comunicação Assíncrona e RabbitMQ

Este projeto é uma aplicação de exemplo baseada em **arquitetura de microsserviços** com **comunicação assíncrona via RabbitMQ**, estruturado para demonstrar conceitos práticos de desacoplamento, escalabilidade e organização de sistemas distribuídos.

## 🌐 Visão Geral

A aplicação é dividida em três microsserviços principais:

- **Serviço Acadêmico**
- **Serviço Financeiro**
- **Serviço de Marketing**

Esses serviços se comunicam de forma assíncrona através de mensagens trocadas por meio do **RabbitMQ**, e a entrada principal da aplicação é controlada por um **API Gateway baseado em NGINX**.

---

## 🎯 Objetivos e Aprendizados

- Aplicar a arquitetura de microsserviços na prática;
- Separar componentes de forma coesa e escalável;
- Estabelecer comunicação assíncrona entre serviços com RabbitMQ;
- Organizar projetos usando abordagem multi-repo e monorepo;
- Compreender vantagens e desvantagens de cada modelo;
- Aprender sobre **submódulos Git**;
- Criar pipelines de integração contínua com **GitHub Actions**;
- Construir um processo de build robusto com validação por pull requests;
- Utilizar práticas dos **12 fatores** para tornar os serviços independentes;
- Propor melhorias como segurança, réplicas e monitoramento com ferramentas como **Grafana** e **Telegraf**.

---

## 🛠️ Tecnologias e Ferramentas

- **Docker** (para orquestração local)
- **RabbitMQ** (mensageria)
- **NGINX** (API Gateway)
- **Git** e **submódulos**
- **GitHub Actions** (CI/CD)
- **Node.js / Express / ou linguagem usada** (substitua aqui conforme seu projeto)
- **Jenkins / Travis (conceitual)**

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Docker e Docker Compose instalados
- Git

### Clonando o Projeto

```bash
git clone https://github.com/Ecov82/alura-ms-main.git
cd alura-ms-main
