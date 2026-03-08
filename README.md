🚀 Docker: Microsserviços com NGINX, PHP e MySQL

Projeto desenvolvido durante o Bootcamp – Accenture | Desenvolvimento Java & Cloud, com foco na utilização prática do Docker em um cenário de microsserviços.

O objetivo do projeto é demonstrar como containers podem ser utilizados para construir uma arquitetura escalável, utilizando Docker, NGINX como proxy reverso, aplicação PHP e banco de dados MySQL, simulando um ambiente distribuído em cluster.

☁️ Contexto: Migração para Nuvem

Muitas empresas estão migrando de infraestrutura privada para nuvem pública devido aos desafios do modelo tradicional.

Problemas comuns da infraestrutura privada

🔐 Segurança física e lógica da infraestrutura

👨‍💻 Necessidade de mão de obra especializada

💻 Alto custo de hardware

⚡ Alto consumo de energia elétrica

🔌 Falhas de energia

💸 Custos inesperados de manutenção

Vantagens da nuvem pública

💰 Pague apenas pelo que utilizar

⚙️ Facilidade de provisionamento

📈 Escalabilidade

🚀 Alta performance

🧩 Arquitetura de Microsserviços

Microsserviços são uma arquitetura onde aplicações são divididas em serviços pequenos e independentes, que se comunicam através de APIs.

Empresas como:

Netflix

Spotify

utilizam esse modelo para operar centenas de microsserviços, permitindo escalar apenas partes específicas do sistema.

Vantagens

✔ Escalabilidade independente

✔ Melhor manutenção

✔ Maior agilidade de desenvolvimento

✔ Possibilidade de múltiplas linguagens

🐳 Docker e Cluster Swarm
Cluster

Um cluster é um conjunto de máquinas que trabalham juntas como se fossem um único sistema.

Cada máquina dentro do cluster é chamada de node.

Docker Swarm

O Docker Swarm é uma ferramenta nativa do Docker que permite:

Orquestração de containers

Distribuição de cargas

Criação de clusters

Escalabilidade automática

🏗 Arquitetura do Projeto

A estrutura do projeto funciona da seguinte forma:

Usuário | NGINX (Proxy Reverso) |Containers PHP (Aplicação) | MySQL (Banco de Dados)

O NGINX atua como Load Balancer, distribuindo requisições entre múltiplos containers da aplicação.

Função da configuração:

Criar um load balancer

Distribuir requisições entre múltiplos servidores

Escalar a aplicação

💻 Aplicação PHP

Arquivo: index.php

A aplicação:

Conecta ao banco MySQL

Gera dados aleatórios

Insere registros na tabela

Mostra a versão atual do PHP

Identifica o host do container

Isso permite visualizar qual container respondeu à requisição, útil para demonstrar balanceamento de carga.

📈 Teste de Escalabilidade

Você pode simular múltiplas requisições usando ferramentas como:

Apache Benchmark

JMeter

K6

Isso ajuda a verificar o funcionamento do load balancer e dos containers.

🧠 Conceitos Aplicados

Este projeto utiliza conceitos importantes de Cloud e DevOps:

Containers

Docker

Microsserviços

Load Balancer

Proxy Reverso

Cluster

Docker Swarm

Infraestrutura escalável

📚 Tecnologias Utilizadas

🐳 Docker

🌐 NGINX

🐘 PHP

🗄 MySQL

🐧 Linux

☁️ Cloud Computing

🎯 Objetivo do Projeto

Demonstrar na prática:

Arquitetura de microsserviços

Uso de containers Docker

Configuração de proxy reverso

Distribuição de carga entre serviços

Integração com banco de dados
