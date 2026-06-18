# Pokedex

Uma aplicação web interativa que simula uma Pokedex, desenvolvida utilizando as tecnologias fundamentais do desenvolvimento web (HTML, CSS e JavaScript). Este projeto consome os dados da [PokéAPI](https://pokeapi.co/) para exibir uma lista dinâmica de Pokémons, demonstrando conceitos importantes como manipulação do DOM, consumo de APIs RESTful e paginação.

## 🚀 Funcionalidades

* **Listagem de Pokémons:** Exibição dinâmica de dados puxados diretamente da PokéAPI.
* **Paginação:** Botão "Load more" para carregar novas páginas de Pokémons sem recarregar a página (comportamento assíncrono).
* **Design Responsivo:** Layout estruturado para se adaptar a diferentes tamanhos de tela.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica da página.
* **CSS3:** Estilização da interface, utilizando `Normalize.css` para consistência entre navegadores e `Bootstrap 5` para classes utilitárias rápidas.
* **JavaScript (ES6+):** Lógica da aplicação, requisições HTTP (Fetch API) e modelagem orientada a objetos.
* **Fontes:** Google Fonts (Roboto).

## 📁 Estrutura do Projeto

Baseado nas importações do `index.html`, o projeto segue uma arquitetura modular em JavaScript:

* `index.html`: Arquivo principal contendo a estrutura da página.
* `/assets/css/global.css` & `pokedex.css`: Arquivos de estilização geral e específica da listagem.
* `/assets/js/pokemon-model.js`: Classe/modelo que mapeia e converte o objeto complexo da PokéAPI para um objeto mais simples e utilizável no front-end.
* `/assets/js/poke-api.js`: Módulo dedicado exclusivamente para o consumo e tratamento das requisições à PokéAPI.
* `/assets/js/main.js`: Lógica principal de manipulação do DOM, injeção do HTML gerado e eventos de clique (como o botão de paginação).

## 💻 Como Executar o Projeto

1. Faça o clone ou o download deste repositório.
2. Certifique-se de que a estrutura de pastas (`/assets/css/`, `/assets/js/`, `/assets/img/`) esteja correta juntamente com o `index.html`.
3. Abra o arquivo `index.html` em qualquer navegador moderno.
   * *Dica:* Para uma melhor experiência de desenvolvimento, você pode utilizar a extensão **Live Server** do VS Code.

---
*Projeto desenvolvido para fins de estudo e aprimoramento no ecossistema front-end.*
