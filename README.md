# Portfólio / Currículo Web — Desenvolvimento de Sistema

Este projeto é uma página de **Portfólio e Currículo Web** desenvolvida em HTML5 puro e semântico. A estrutura foi criada como parte do desafio prático do curso de Desenvolvimento de Sistemas do SENAI.

O objetivo principal é demonstrar a correta utilização das tags semânticas da Web para organizar dados pessoais, habilidades, histórico de projetos e um formulário de contato funcional.

---

## 📌 Conteúdo da Página

A página está dividida em 4 seções principais organizadas de forma lógica e acessível:

1. **Cabeçalho & Navegação (`<header>`, `<nav>`):** 
   - Título principal com nome e cargo.
   - Menu de navegação interna por âncoras (`#sobre`, `#projetos`, `#contato`).

2. **Sobre Mim (`<section id="sobre">`):**
   - Imagem de perfil no padrão 150x150px.
   - Resumo acadêmico e tecnologias em aprendizado.
   - Lista não ordenada (`<ul>`) detalhando as principais habilidades técnicas.

3. **Meus Projetos (`<section id="projetos">`):**
   - Tabela semântica (`<table>`, `<thead>`, `<tbody>`, `<th>`, `<td>`) listando os projetos desenvolvidos, suas respectivas tecnologias, status atual e links.

4. **Entre em Contato (`<section id="contato">`):**
   - Formulário embutido em um `<fieldset>` com a legenda *"Dados do Contato"*.
   - Campos com rótulos (`<label>`) associados para *Nome*, *Email*, *Assunto* (menu suspenso `<select>`) e *Mensagem* (`<textarea>`).
   - Botão de envio (`<input type="submit">`).

5. **Rodapé (`<footer>`):**
   - Direitos autorais utilizando o caractere especial `&copy;`.
   - Hiperlinks diretos para e-mail (`mailto:`) e telefone de contato (`tel:`).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Sem o uso de frameworks externos, focando no domínio das tags semânticas nativas da linguagem de marcação.