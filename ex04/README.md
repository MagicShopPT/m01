Trabalho realizado por: *Vitor Silva* (**13422**)

**Curso:** Licenciatura em Informática (SE) - Instituto Superior Miguel Torga (ISMT)

**Unidade Curricular:** Programação WEB

**Data de Submissão:** 19 de novembro de 2026

# Módulo 01 — HTML5 e Semântica

Este projeto corresponde à resolução dos exercícios práticos do Módulo 01 da unidade curricular de Programação WEB, focado na estruturação de documentos web, aplicação de HTML5 semântico e criação de formulários acessíveis.

## Lista de Exercícios Realizados

* [x] **EX01** — First Page (Página Pessoal)
* [x] **EX02** — Semantic Profile (Perfil Pessoal Semântico)
* [x] **EX03** — News Page (Jornal Tecnológico TechNews + Bónus)
* [x] **EX04** — Contact Form (Formulário de Contacto Profissional + Bónus)

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

### EX03 — News Page

O terceiro exercício teve como objetivo desenvolver a página inicial de um pequeno jornal tecnológico (**TechNews**), trabalhando a hierarquia de títulos, artigos independentes, listas, imagens e hiperligações, utilizando exclusivamente HTML5.

**Principais tomadas de decisão e aspetos técnicos relevantes:**

* **Organização por Categorias e Navegação:** O menu de navegação (`<nav>`) utiliza âncoras internas (`#tecnologia`, `#programacao`, `#ia`, `#seguranca`) para permitir o acesso rápido às diferentes secções temáticas (`<section>`) da página principal.
* **Consistência Estrutural dos Artigos:** Foram criadas cinco notícias distintas encapsuladas em elementos `<article>`. Todas seguem rigorosamente a mesma estrutura interna (título `<h3>`, linha de metadados com autor, data semântica `<time>` e categoria, imagem local `<img>` otimizada em formatos modernos `.webp`/`.avif` com atributo `alt` descritivo, parágrafo de resumo e hiperligação para leitura completa).
* **Implementação do Bónus (Páginas Individuais):** Para cumprir o requisito bónus em HTML estático puro, cada notícia na página inicial (`index.html`) aponta diretamente para um ficheiro HTML independente (`noticia-1.html` a `noticia-5.html`) na mesma diretoria. Cada página individual mantém a consistência visual/estrutural com a imagem correspondente, o texto completo do artigo e navegação direta de regresso à página inicial.

### EX04 — Contact Form

O quarto exercício teve como objetivo construir um formulário de contacto profissional acessível e funcional utilizando apenas **HTML5 puro** (sem JavaScript ou CSS), recorrendo aos mecanismos nativos de validação do navegador.

**Principais tomadas de decisão e aspetos técnicos relevantes:**

* **Agrupamento Lógico e Acessibilidade:** O formulário (`<form>`) foi organizado com elementos `<fieldset>` e `<legend>` para separar os dados pessoais dos detalhes do pedido. Todos os campos (`<input>`, `<select>`, `<textarea>`) estão explicitamente associados a uma etiqueta `<label>` através da correspondência exata entre os atributos `for` e `id`.
* **Tipos de Dados Semânticos:** Foram aplicados tipos específicos nos inputs (`type="text"`, `type="email"`, `type="tel"` e `type="checkbox"`), facilitando a usabilidade em dispositivos móveis e permitindo ao navegador interpretar a natureza de cada dado.
* **Implementação do Bónus (Validação HTML5):** Para cumprir a restrição de não utilizar JavaScript e assegurar a integridade dos dados submetidos, foram aplicados atributos nativos de validação HTML5: `required` nos campos obrigatórios, `minlength` e `maxlength` para limitar o tamanho do texto, validação automática de formato de e-mail (`type="email"`), e expressão regular `pattern="[0-9]{9}"` com atributo `title` explicativo para validar o número de telefone com 9 dígitos.

## Tecnologias Utilizadas

* HTML5 (puro, sem CSS ou JavaScript)

## Como Executar

1. Abrir a pasta do projeto (`M01`) no editor de código (ex: Visual Studio Code).
2. Abrir o ficheiro `index.html` da pasta do exercício pretendido (`ex01/`, `ex02/`, `ex03/` ou `ex04/`) diretamente num navegador web, ou utilizar a extensão **Live Server**.

## Estrutura do Projeto

```text
M01/
├── ex01/
│   ├── index.html
│   └── README.md
├── ex02/
│   ├── index.html
│   └── README.md
├── ex03/
│   ├── index.html
│   ├── noticia-1.html
│   ├── noticia-2.html
│   ├── noticia-3.html
│   ├── noticia-4.html
│   ├── noticia-5.html
│   ├── tecnologia.webp
│   ├── codigo.webp
│   ├── versoes.webp
│   ├── ia.webp
│   ├── cadeado.avif
│   └── README.md
├── ex04/
│   ├── index.html
│   └── README.md
└── README.md
```

## Autor

**Vitor Silva** (Aluno n.º 13422)

* GitHub: [MagicShopPT](https://github.com/MagicShopPT)