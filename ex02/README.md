Trabalho realizado por: *Vitor Silva* (**13422**)

**Curso:** Licenciatura em Informática (SE) - Instituto Superior Miguel Torga (ISMT)

**Unidade Curricular:** Programação WEB

**Data de Submissão:** 19 de novembro de 2026

# Módulo 01 — HTML5 e Semântica

Este projeto corresponde à resolução dos exercícios práticos do Módulo 01 da unidade curricular de Programação WEB, focado na estruturação de documentos web e na aplicação rigorosa de HTML5 semântico.

## Lista de Exercícios Realizados

* [x] **EX01** — First Page (Página Pessoal)
* [x] **EX02** — Semantic Profile (Perfil Pessoal Semântico)

## Descrição dos Exercícios e Tomadas de Decisão

### EX01 — First Page

O objetivo deste primeiro exercício consistiu na criação de uma página web pessoal estática para um programador, utilizando exclusivamente **HTML5 puro** (sem recurso a folhas de estilo CSS ou scripts JavaScript).

**Principais tomadas de decisão e aspetos técnicos relevantes:**

* **Semântica e Acessibilidade:** Optou-se pela utilização rigorosa das tags semânticas do HTML5 (`<header>`, `<main>`, `<section>` e `<footer>`) em detrimento de contentores genéricos (`<div>`). Esta decisão melhora a leitura do código, facilita a indexação por motores de busca (SEO) e garante compatibilidade com leitores de ecrã.
* **Estruturação de Conteúdo:** A informação foi dividida logicamente em secções distintas: apresentação pessoal (com imagem e atributo `alt` descritivo), uma lista não ordenada (`<ul>`) para os interesses e outra lista com hiperligações funcionais (`mailto:` e link externo com `target="_blank"`) para os contactos.
* **Conformidade com Restrições:** Todo o layout e hierarquia visual foram assegurados apenas pela semântica nativa das tags HTML (como a hierarquia de títulos `<h1>` e `<h2>`), respeitando integralmente a restrição de não utilizar CSS ou JavaScript.

### EX02 — Semantic Profile

O segundo exercício teve como objetivo evoluir o perfil pessoal para uma estrutura semântica completa e bem organizada, eliminando contentores genéricos desnecessários e introduzindo navegação interna.

**Principais tomadas de decisão e aspetos técnicos relevantes:**

* **Arquitetura Semântica Completa:** Foram aplicados todos os elementos estruturais solicitados (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` e `<footer>`), evitando o uso de `<div>`. Cada secção do perfil (Biografia, Competências, Projetos e Contactos) tem uma função estrutural clara.
* **Papel Semântico do `<aside>`:** O elemento `<aside>` foi utilizado para apresentar uma nota complementar/curiosidade sobre boas práticas de HTML. Mesmo sem CSS para o posicionar visualmente como uma barra lateral física, a sua inclusão garante o significado semântico correto para leitores de ecrã e motores de busca.
* **Navegação Interna por Âncoras:** Foram definidos atributos `id` únicos nas principais secções da página e criadas ligações no menu `<nav>` com referências `#id`, permitindo saltar diretamente para cada secção do documento.
* **Interligação entre Exercícios:** Foi adicionado um link relativo (`../ex01/index.html`) com o atributo `target="_blank"` para permitir abrir o projeto anterior numa nova aba sem perder o contexto da página atual.

## Tecnologias Utilizadas

* HTML5 (puro, sem CSS ou JavaScript)

## Como Executar

1. Abrir a pasta do projeto no editor de código (ex: Visual Studio Code).
2. Abrir o ficheiro `index.html` da pasta do exercício pretendido (`ex01/` ou `ex02/`) diretamente num navegador web, ou utilizar a extensão **Live Server**.

## Estrutura do Projeto

```text
Modulo 01/
├── ex01/
│   └── index.html
|   └── README.md
├── ex02/
│   └── index.html
|   └── README.md
└── README.md
```

## Autor

**Vitor Silva**

* GitHub: [MagicShopPT](https://github.com/MagicShopPT)