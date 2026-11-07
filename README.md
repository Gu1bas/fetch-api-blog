# Blog com Fetch API

Uma aplicação de blog interativa desenvolvida em JavaScript Vanilla consumindo a API REST do [JSONPlaceholder](https://jsonplaceholder.typicode.com/) através da Fetch API e requisições assíncronas.

> Projeto desenvolvido durante os estudos do curso de JavaScript do instrutor **Matheus Battisti (Hora de Codar)**.

---

## Funcionalidades

- [x] **Listagem de Posts:** Carregamento dinâmico e exibição de artigos no feed principal.
- [x] **Página de Post Individual:** Roteamento com parâmetros de URL (`?id=`) para exibir o post selecionado.
- [x] **Requisições Paralelas:** Carregamento simultâneo dos dados do post e dos seus respectivos comentários via `Promise.all`.
- [x] **Envio de Comentários (POST):** Formulário interativo para envio de novos comentários via requisição HTTP POST em formato JSON.
- [x] **Feedback Visual de Carregamento:** Indicador visual de loading enquanto os dados da API são processados.

---

## Tecnologias Utilizadas

- **HTML5:** Estrutura semântica para feed, páginas de post e formulários de comentários.
- **CSS3:** Estilização limpa e responsiva com classes utilitárias.
- **JavaScript (ES6+):** Lógica assíncrona, Fetch API e manipulação dinâmica do DOM.
- **JSONPlaceholder API:** Mock de API REST pública para operações de leitura e escrita.

---

## Conceitos Praticados

- **Requisições Assíncronas:** Uso de `fetch`, `async/await` e manipulação de Promises com `Promise.all`.
- **Métodos HTTP e Headers:** Implementação de requisições `GET` e `POST` com cabeçalhos `application/json` e serialização com `JSON.stringify`.
- **Roteamento e Query Parameters:** Leitura de parâmetros de busca na URL via `URLSearchParams`.
- **Manipulação Dinâmica do DOM:** Criação de elementos em tempo de execução com `document.createElement`, `innerText`, `setAttribute` e `appendChild`.
