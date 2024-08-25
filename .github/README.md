![git-favorites](https://github.com/user-attachments/assets/39dca365-107f-4d52-b7ff-5ed99d3cc43a)
## 🖥️ Projeto

O Github Favorites é um projeto desenvolvido em aula durante o Stage 06 da trilha Explorer da Rocketseat. Esse projeto permite aos usuários buscar perfis de usuários do Github e salvar seus favoritos em uma lista que é armazenada localmente no navegador.

## 🚀 Tecnologias

Esse projeto foi desenvolvido utilizando as seguintes tecnologias:

- HTML
- CSS
- Javascript
- Git e Github

## 💡 Técnicas Utilizadas

- **Integração com API do Github:** A aplicação consulta a API do GitHub para obter os detalhes do usuário.

- **localStorage:** Aqui aprendemos os conceitos do localStorage. Os usuários adicionados são salvos no localStorage, permitindo que a lista de favoritos seja preservada mesmo ao recarregar a página.

- **ES6 Modules:** O uso de ES Modules permite um gerenciamento mais eficiente das dependências e do escopo no JS.

- **API Fetch e Promises:** `fetch` é uma função assíncrona que faz solicitações HTTP e retorna uma `Promise`. As `Promises` permitem lidar com operações assíncronas de forma mais eficiente do que callbacks.

- **Classes JS:** 
  **GithubUser**: Classe responsável por buscar dados da API do GitHub para um determinado usuário.
  **Favorites**: Responsável por gerenciar a lógica de armazenamento dos usuários favoritos, usando o localStorage para persistir os dados entre sessões.
  **FavoritesView**: Extende a classe `Favorites` e é responsável por manipular o DOM, criando a interface visual para exibir os dados dos usuários favoritos e configurar eventos, como adicionar ou remover um usuário da lista.
