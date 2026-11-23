Trabalho realizado por: *Vitor Silva* (**13422**)

**Curso:** Licenciatura em Informática (SE) - Instituto Superior Miguel Torga (ISMT)  
**Unidade Curricular:** Programação WEB  
**Data de Submissão:** 18 de novembro de 2026

# Módulo 01 — HTML5 e Semântica

Este projeto corresponde à resolução dos exercícios práticos do Módulo 01 da unidade curricular de Programação WEB.

## Lista de Exercícios Realizados
- [x] **EX01** — First Page (Página Pessoal)

## Descrição dos Exercícios e Tomadas de Decisão

### EX01 — First Page
O objetivo deste primeiro exercício consistiu na criação de uma página web pessoal estática para um programador, utilizando exclusivamente **HTML5 puro** (sem recurso a folhas de estilo CSS ou scripts JavaScript).

**Principais tomadas de decisão e aspetos técnicos relevantes:**
* **Semântica e Acessibilidade:** Optou-se pela utilização rigorosa das tags semânticas do HTML5 (`<header>`, `<main>`, `<section>` e `<footer>`) em detrimento de contentores genéricos (`<div>`). Esta decisão melhora a leitura do código, facilita a indexação por motores de busca (SEO) e garante compatibilidade com leitores de ecrã.
* **Estruturação de Conteúdo:** A informação foi dividida logicamente em secções distintas: apresentação pessoal (com imagem e atributo `alt` descritivo), uma lista não ordenada (`<ul>`) para os interesses e outra lista com hiperligações funcionais (`mailto:` e link externo com `target="_blank"`) para os contactos.
* **Conformidade com Restrições:** Todo o layout e hierarquia visual foram assegurados apenas pela semântica nativa das tags HTML (como a hierarquia de títulos `<h1>` e `<h2>`), respeitando integralmente a restrição de não utilizar CSS ou JavaScript.

## Tecnologias Utilizadas
- HTML5 (puro, sem CSS ou JavaScript)

## Como Executar
1. Abrir a pasta do projeto no editor de código (ex: Visual Studio Code).
2. Abrir o ficheiro `index.html` diretamente num navegador web ou utilizar a extensão **Live Server**.

## Estrutura do Projeto
```text
Modulo 01/
├── EX01/
│   └── index.html
|   └── README.md
└── README.md
```

## Autor
**Vitor Silva**
- GitHub: [MagicShopPT](https://github.com/MagicShopPT)