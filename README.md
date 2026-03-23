# lab02-Entendendo-o-Desafio---Armazenando-dados-de-um-E-Commerce-na-Cloud
📌 Armazenando Dados de um E-Commerce na Cloud

Este projeto foi desenvolvido como parte de um laboratório prático da Digital Innovation One, com o objetivo de aplicar conceitos fundamentais de computação em nuvem, conteinerização e orquestração de aplicações.

A proposta consiste em simular um ambiente de e-commerce utilizando tecnologias modernas, permitindo compreender como aplicações podem ser armazenadas, distribuídas e escaladas na cloud de forma eficiente.

🚀 Tecnologias Utilizadas
🐳 Docker
🌐 Nginx
☸️ Kubernetes
☁️ Microsoft Azure
YAML (configuração de serviços e deployments)
🛠️ Estrutura do Projeto

O projeto foi estruturado com os seguintes arquivos:

Dockerfile → Responsável por criar a imagem da aplicação
index.html → Página web simulando o front-end do e-commerce
deployment.yaml → Define como a aplicação será implantada no Kubernetes
service.yaml → Responsável por expor a aplicação
comandos.txt → Contém comandos utilizados durante o desenvolvimento
⚙️ Etapas Realizadas

Durante o desenvolvimento, foram realizadas as seguintes etapas:

1. Criação da Aplicação Web

Foi desenvolvido um arquivo index.html simples para simular a interface de um sistema de e-commerce.

2. Conteinerização com Docker

Foi criado um Dockerfile utilizando a imagem oficial do Nginx:

Utilização do Nginx como servidor web
Substituição da página padrão pelo index.html
Criação de uma imagem leve e eficiente
3. Execução do Container

A aplicação foi executada localmente utilizando Docker, permitindo acesso via navegador.

4. Configuração para Kubernetes

Foram criados arquivos de configuração:

deployment.yaml → Gerenciamento dos pods e escalabilidade
service.yaml → Exposição da aplicação para acesso externo
5. Conceitos Aplicados
Conteinerização de aplicações
Orquestração com Kubernetes
Escalabilidade de sistemas
Alta disponibilidade
Separação entre infraestrutura e aplicação
📚 Aprendizados

Durante este projeto, foi possível compreender:

Como transformar uma aplicação simples em um container
A importância do uso de containers no desenvolvimento moderno
Como o Kubernetes gerencia aplicações em larga escala
A diferença entre rodar localmente e em ambiente cloud
Como serviços em nuvem facilitam o deploy e gerenciamento de aplicações
💡 Insights

Um dos principais aprendizados foi entender como empresas utilizam tecnologias como Docker e Kubernetes para garantir que suas aplicações sejam:

Escaláveis
Confiáveis
Fáceis de manter

Além disso, ficou evidente que a computação em nuvem é essencial para aplicações modernas, especialmente em sistemas como e-commerce, que demandam alta disponibilidade e desempenho.

📸 Evidências

Adicione aqui prints do:

Container rodando
Aplicação no navegador
Configurações no Kubernetes
🔗 Referência do Projeto

Projeto base fornecido pela DIO:
https://github.com/digitalinnovationone/Microsoft_Application_Platform
