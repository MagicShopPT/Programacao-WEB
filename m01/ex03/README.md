Trabalho realizado por: *Vitor Silva* (**12345**)

**Curso:** Licenciatura em Informática (DS / SE) - Instituto Superior Miguel Torga (ISMT)

**Unidade Curricular:** Programação WEB

**Data de Submissão:** 19 de novembro de 2026

# Módulo 01 — HTML5 e Semântica

Este projeto corresponde à resolução dos exercícios práticos do Módulo 01 da unidade curricular de Programação WEB, focado na estruturação de documentos web e na aplicação rigorosa de HTML5 semântico.

## Lista de Exercícios Realizados

* [x] **EX01** — First Page (Página Pessoal)
* [x] **EX02** — Semantic Profile (Perfil Pessoal Semântico)
* [x] **EX03** — News Page (Jornal Tecnológico TechNews + Bónus)
* [ ] **EX04** — *(Adicionar título do exercício quando concluído)*
* [ ] **EX05** — *(Adicionar título do exercício quando concluído)*

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
* **Consistência Estrutural dos Artigos:** Foram criadas cinco notícias distintas encapsuladas em elementos `<article>`. Todas seguem rigorosamente a mesma estrutura interna (título `<h3>`, linha de metadados com autor, data semântica `<time>` e categoria, imagem `<img>` com `alt` descritivo, parágrafo de resumo e hiperligação para leitura completa).
* **Implementação do Bónus (Páginas Individuais):** Para cumprir o requisito bónus em HTML estático puro, cada notícia na página inicial (`index.html`) aponta para um ficheiro HTML individual (`noticia-1.html` a `noticia-5.html`). Cada página individual contém o desenvolvimento completo do respetivo artigo e um link de navegação para regressar à página inicial.

## Tecnologias Utilizadas

* HTML5 (puro, sem CSS ou JavaScript)

## Como Executar

1. Abrir a pasta do projeto no editor de código (ex: Visual Studio Code).
2. Abrir o ficheiro `index.html` da pasta do exercício pretendido (`ex01/`, `ex02/` ou `ex03/`) diretamente num navegador web, ou utilizar a extensão **Live Server**.

## Estrutura do Projeto

```text
Modulo 01/
├── ex01/
│   └── index.html
├── ex02/
│   └── index.html
├── ex03/
│   ├── index.html
│   ├── noticia-1.html
│   ├── noticia-2.html
│   ├── noticia-3.html
│   ├── noticia-4.html
│   └── noticia-5.html
└── README.md
```

## Autor

**Vitor Silva**

* GitHub: [MagicShopPT](https://github.com/MagicShopPT)