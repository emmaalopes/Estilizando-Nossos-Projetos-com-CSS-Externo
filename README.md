# 🚀 Exercícios de Desenvolvimento Web: HTML5 & CSS3

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Este repositório reúne um conjunto de exercícios práticos focados na aprendizagem de **HTML5** e **CSS3**, abrangendo a criação de interfaces temáticas de estilo *arcade*, a estruturação semântica de páginas web, a criação de tabelas financeiras e a integração de multimédia.

---

## 📁 Estrutura do Repositório

| Ficheiros | Descrição |
| :--- | :--- |
| `05_desafio.html` / `05_desafio.css` | **GameZone Retro**: Página temática de estilo 8-bit com animações néon e tabela de preços[cite: 1, 2]. |
| `07_semantica.html` / `07_semantica.css` | **Layout Semântico**: Estrutura moderna desenvolvida com tags semânticas e distribuição Flexbox[cite: 3, 4]. |
| `08_multimidia.html` / `08_multimidia.css` | **Multimédia e Tabelas**: Relatório de vendas estruturado e leitores de áudio/vídeo[cite: 5, 6]. |

---

## 🕹️ Conteúdo e Funcionalidades

### 1. GameZone Retro (Desafio 8-Bit)
* **Design Retro**: Utilização de fundos escuros com gradientes e tipografia monoespaçada[cite: 1].
* **Animações em CSS**: Efeito néon no título através da regra `@keyframes piscar`[cite: 1].
* **Catálogo de Consolas**: Lista de equipamentos disponíveis (NES, SNES, Sega Genesis e Atari 2600).
* **Tabela de Preços**: Apresentação de valores para jogos clássicos como Super Mario Bross, Sonic e Zelda[cite: 2].
* **Navegação**: Hiperligações para secções da página e ligação externa para o Instagram[cite: 2].

### 2. Estrutura Semântica & Flexbox
* **Elementos do HTML5**: Organização do conteúdo com as tags `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>` e `<footer>`.
* **Disposição em Flexbox**: Menu horizontal e separação flexível entre a área principal e a barra lateral[cite: 3].
* **Acessibilidade e Dados**: Utilização do elemento `<time>` com o atributo `datetime`[cite: 4].
* **Informações de Contacto**: Formatação de e-mail e hiperligações através da tag `<address>`[cite: 4].

### 3. Relatório Financeiro e Multimédia
* **Tabelas Avançadas**: Estruturação de dados financeiros recorrendo a `<caption>`, `<thead>`, `<tbody>` e `<tfoot>`.
* **Vídeo Local**: Incorporação do ficheiro `meu-video.mp4` com imagem de capa (`poster="assets/limoes-capa.png"`)[cite: 6].
* **Vídeo do YouTube**: Inclusão de um elemento `<iframe>` com regras de responsividade[cite: 5, 6].
* **Leitor de Áudio**: Reprodução do ficheiro `happy-mistake.mp3` utilizando a tag `<audio>`[cite: 6].

---

## 📂 Estrutura da Pasta de Recursos (Assets)

Para garantir a apresentação correta de todas as imagens e ficheiros multimédia, mantenha a seguinte organização na pasta `assets/`:

```text
assets/
├── retro.jpg
├── limoes-capa.png
├── meu-video.mp4
└── happy-mistake.mp3
