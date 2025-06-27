# 🧪 Testes Manuais - Swag Labs

Este repositório contém a documentação e os artefatos relacionados aos **testes manuais** realizados no sistema **Swag Labs**, simulando uma aplicação de e-commerce com foco em funcionalidades essenciais como login, catálogo de produtos, carrinho de compras e checkout.

---

## 📌 Objetivo

O objetivo deste projeto é aplicar conceitos de **testes manuais funcionais**, explorando técnicas de:
- Criação de casos de testes
- Execução de testes positivos e negativos
- Identificação de bugs e documentação via relatórios
- Organização de evidências visuais
- Aplicação prática do STLC (Software Testing Life Cycle)

---

## 🛠️ Tecnologias e Ferramentas

- Sistema de simulação de testes: [Swag Labs]([https://www.saucedemo.com/](https://www.saucedemo.com/v1/index.html))
- Documentação: Google Planilhas e Markdown (`.md`)
- Organização dos arquivos: Estrutura de pastas organizada por feature
- Evidências: Capturas de tela (.png) salvas na pasta `evidencias-bug-report`

---

## ✅ Critérios de Aceitação

Cada funcionalidade testada neste projeto foi validada com base em **critérios de aceitação claros**, incluindo:

- Acesso às páginas e componentes corretos
- Exibição de dados essenciais (nome, imagem, preço, etc.)
- Mensagens de erro apropriadas para campos obrigatórios ou inválidos
- Comportamento esperado dos botões (ex: adicionar/remover do carrinho)
- Respostas visuais (UI) e funcionais consistentes com os requisitos

Esses critérios garantem que o sistema entregue uma **experiência funcional, fluida e sem falhas ao usuário final**.

---

## 📋 Funcionalidades Testadas

- ✅ Login com diferentes tipos de usuário
- ✅ Visualização e filtragem de produtos
- ✅ Adição e remoção de itens no carrinho
- ✅ Preenchimento de formulário de informações de entrega
- ✅ Visualização do resumo de compra
- ❌ Bugs identificados e documentados

---

## 🐞 Relatórios de Bugs

Todos os bugs identificados durante a execução foram documentados na pasta [`/bugs-report`](./bugs-report) com:
- **Descrição completa do erro**
- **Passos para reprodução**
- **Resultado esperado vs. resultado encontrado**
- **Prioridade e tipo de teste**
- **Evidências em imagem**

---

## ✅ Casos de Teste

Os casos de testes estão organizados por feature na pasta [`/features`](./features) e seguem o formato:

- Pré-condições
- Passos
- Resultado esperado
- Status (Passou/Falhou)
- Resultado encontrado (quando aplicável)

