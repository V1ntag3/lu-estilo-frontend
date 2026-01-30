# 🛍️ Lu Estilo – Mini E-commerce Front-End

Este repositório contém o projeto **Lu Estilo**, um mini sistema de e-commerce desenvolvido como parte de um **teste técnico para processo seletivo**.

O projeto foi focado no desenvolvimento do **front-end**, simulando uma loja virtual com funcionalidades essenciais de compra e navegação.

A aplicação está hospedada na plataforma **Netlify** e pode ser acessada em:

🔗 [https://lu-estilo.netlify.app](https://lu-estilo.netlify.app)

---

## 📌 Sobre o Projeto

O Lu Estilo é uma aplicação web que simula um pequeno e-commerce, permitindo que usuários naveguem por produtos, realizem pesquisas, adicionem itens ao carrinho e finalizem compras.

O principal objetivo do projeto foi demonstrar habilidades em:

* Desenvolvimento front-end
* Consumo de APIs externas
* Organização de componentes
* Criação de interfaces responsivas
* Fluxo de compra (checkout)

Este projeto foi utilizado como avaliação prática em um processo seletivo.

---

## ⚠️ Observação Importante (HTTPS e API)

O site está hospedado no Netlify, que utiliza **HTTPS por padrão**.

Entretanto, a aplicação consome uma **API de terceiros via HTTP**, o que pode causar bloqueio de conteúdo misto (mixed content) nos navegadores.

Para utilizar corretamente todas as funcionalidades, pode ser necessário:

* Permitir conteúdo não seguro no navegador
* Autorizar manualmente a execução da API

Isso depende das configurações de segurança do navegador utilizado.

---

## ✨ Funcionalidades

* Listagem de produtos
* Pesquisa de produtos
* Tela de visualização detalhada
* Carrinho de compras
* Checkout
* Simulação de fluxo de compra
* Interface responsiva

---

## 🛠️ Tecnologias Utilizadas

* JavaScript
* Vue.js
* Yarn
* HTML5
* CSS3
* API Externa (HTTP)
* Netlify (Deploy)

---

## 📂 Estrutura do Projeto

```
lu-estilo
│
├── src/        # Código-fonte
├── public/     # Arquivos públicos
├── package.json
└── yarn.lock
```

---

## 📥 Instalação e Execução Local

### Requisitos

* Node.js
* Yarn

### Passos

1. Instale as dependências:

```bash
yarn install
```

2. Inicie o servidor de desenvolvimento:

```bash
yarn serve
```

3. Gere a versão de produção:

```bash
yarn build
```

4. Execute o linter:

```bash
yarn lint
```

---

## 🎯 Objetivos do Projeto

* Avaliar competências em front-end
* Desenvolver um mini e-commerce funcional
* Trabalhar com consumo de APIs
* Criar experiência de usuário intuitiva
* Aplicar boas práticas de organização

---

## 📚 Aprendizados

Com este projeto, foi possível:

* Simular um sistema real de e-commerce
* Trabalhar com integração de APIs externas
* Entender desafios de segurança (HTTP x HTTPS)
* Aprimorar habilidades em Vue.js
* Desenvolver interfaces focadas no usuário

---

## 🚀 Como Utilizar o Sistema

1. Acesse o site
2. Navegue pelos produtos
3. Utilize a busca
4. Adicione itens ao carrinho
5. Realize o checkout

Caso haja bloqueio da API, ajuste as permissões do navegador.

---
