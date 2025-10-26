# ONG Platform - Entrega 1 (HTML5)

Projeto demonstrativo para disciplina de Front-end — entrega 1 (HTML5 + formulários semânticos).

## Estrutura
- index.html — página institucional
- projetos.html — listagem de projetos
- cadastro.html — formulário de cadastro (voluntário/doador)
- css/styles.css
- js/main.js
- images/*

## Requisitos atendidos
- HTML5 semântico
- Formulários com validação nativa e máscaras
- Responsivo (mobile-first)
- Acessibilidade básica (WCAG 2.1 AA target)
- Instruções para validação W3C

## Como rodar
Abrir os arquivos HTML no navegador. Para uma entrega via GitHub Pages:
1. Criar repositório público.
2. Subir os arquivos na branch `main`.
3. Habilitar GitHub Pages nas configurações (pasta `/`).
4. Compartilhar o link público.

## Contato
Responsável: [Seu nome] — email: contato@seuemail.org
# 💡 Farol Digital - Plataforma de Inclusão Digital (Front-End Challenge)

Projeto demonstrativo para a disciplina de Desenvolvimento Front-End. Esta entrega aplica e integra os padrões de HTML5, CSS3 Responsivo e JavaScript, com foco em acessibilidade e performance.

## 🎯 Requisitos Chave Atendidos

A implementação do projeto Farol Digital cumpre integralmente os seguintes objetivos:

| Requisito | Implementação Técnica Detalhada |
| :--- | :--- |
| **HTML5 Semântico** | Aplicação completa de tags estruturais (`<header>`, `<main>`, `<section>`, `<article>`) e hierarquia de títulos (`h1` a `h4`). |
| **Formulário Complexo** | `cadastro.html` utiliza `<fieldset>` e `<legend>` para agrupamento lógico de dados. Uso correto de atributos `autocomplete` e tipos de `input` HTML5 (date, email, tel). |
| **Validação Nativa** | Uso dos atributos `required` e `pattern` (para CPF, CEP) no HTML, garantindo a validação antes da submissão. |
| **Máscaras JS** | O arquivo `js/main.js` implementa máscaras interativas (CPF, Telefone, CEP) e lógica de validação avançada, focando o cursor no primeiro campo inválido para melhor usabilidade (UX). |
| **Design Responsivo** | Arquitetura Mobile-First com CSS Grid e Flexbox. Uso de Media Queries (breakpoints em 700px e 1000px) para layouts adaptativos. |
| **Acessibilidade (WCAG)** | Implementação de `skip-link` e uso de atributos ARIA (`aria-label`, `aria-current`), garantindo navegabilidade por teclado e suporte a leitores de tela. |
| **Performance/Assets** | Imagens otimizadas em **múltiplos formatos** (JPG para fotos, SVG para logo), comprimidas e redimensionadas para o tamanho de exibição no layout. Uso de `loading="lazy"`. |

## 🛠️ Tecnologias Utilizadas
* **HTML5** (Semântica e Acessibilidade)
* **CSS3** (Variáveis CSS, Mobile-First, Flexbox/Grid)
* **JavaScript ES6** (Máscaras de Input, Manipulação de DOM)

## 📂 Estrutura do Repositório

farol-digital-plataforma/ |-- index.html # Página Institucional |-- projetos.html # Listagem de Projetos (Grid Responsivo) |-- cadastro.html # Formulário Complexo |-- README.md # Este Documento |-- css/ | |-- styles.css # Estilos Responsivos |-- js/ | |-- main.js # Máscaras e Validação |-- images/ | |-- *.jpg, *.svg # Assets Otimizados (Fotos e Logo)

## 📋 Comprovação de Web Standards (W3C)

Todos os arquivos HTML foram verificados e **validados com sucesso** no W3C Markup Validation Service, garantindo a conformidade com os padrões da web.

---
Responsável: [Leonardo Juliani Costa]
Link PÚBLICO do Projeto no GitHub: `[INSIRA O LINK DO SEU REPOSITÓRIO PÚBLICO AQUI]`
