# MetaAssist — Game Meta Assistant

Este repositório contém a implementação do **MetaAssist**, uma aplicação web front-end que integra **IA generativa (Google Gemini)** para fornecer respostas objetivas e contextualizadas sobre **meta, builds e estratégias** de jogos competitivos.

O projeto demonstra a aplicação prática de **consumo de APIs externas**, manipulação assíncrona de dados, renderização dinâmica de conteúdo e preocupação com clareza de interface e experiência do usuário.

---

## 📌 Contexto e Propósito

O MetaAssist foi desenvolvido no contexto de aprendizado durante um **curso/evento da Alura (NLW)**, com foco em:

- Integração de aplicações web com **modelos de linguagem**
- Uso de **JavaScript moderno (ES6+)**
- Estruturação de prompts e controle de respostas da IA
- Desenvolvimento de interfaces leves, responsivas e funcionais

O repositório atua como uma **prova de conceito funcional**, demonstrando domínio técnico e capacidade de integrar tecnologias emergentes em aplicações web.

---

##  Visão Geral da Arquitetura

A aplicação opera inteiramente no front-end, realizando chamadas diretas à **API do Google Gemini** mediante fornecimento explícito da API Key pelo usuário.

Fluxo geral:
1. Coleta de entrada do usuário (API Key, jogo e pergunta)
2. Construção dinâmica de prompt especializado
3. Requisição assíncrona à API do Gemini
4. Processamento da resposta em Markdown
5. Conversão e renderização em HTML no DOM

---

##  Funcionalidades Implementadas

- Integração com **Google Gemini API**
- Seleção dinâmica de contexto por jogo
- Geração de respostas técnicas focadas em meta atual
- Renderização de respostas em **Markdown**
- Conversão de Markdown para HTML via **Showdown.js**
- Validação de formulário e controle de estado
- Feedback visual durante requisições assíncronas
- Animações e transições para melhor UX

---

##  Tecnologias e Ferramentas

- **HTML5** — Estrutura semântica  
- **CSS3** — Layout, animações e responsividade  
- **JavaScript (ES6+)** — Lógica de negócio e integração com API  
- **Google Gemini API** — IA generativa  
- **Showdown.js** — Parser Markdown → HTML  
- **Google Fonts (Inter)**  

---


