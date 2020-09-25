<p align="right">
  <a href="README.en.md">🇺🇸</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.md">🇧🇷</a>&nbsp;&nbsp;&nbsp;
</p>

<img alt="GoStack" src=./src/assets/header-bootcamp.png />

<h3 align="center">
  Conceitos do Node.js
</h3>

<p align="center">
  <a href="#rocket-sobre-a-aplicação">Sobre a aplicação</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#cd-pacotes-instalados">Pacotes instalados</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<img alt="Insomnia" src=./src/assets/screen-insomnia.gif />

## :rocket: Sobre a aplicação

Uma simples aplicação em Node.js!

Essa é uma aplicação para armazenar projetos do seu portfólio, que permite a criação, listagem, atualização e remoção dos projetos.

### Rotas da aplicação

No arquivo index.js:

- **`POST /projects`**: A rota deve receber `title` e `owner` dentro do corpo da requisição. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato: `{ id: "uuid", title: 'Project X', owner: 'Bruno' }`;

- **`GET /projects`**: Rota que lista todos os projetos;

- **`PUT /projects/:id`**: A rota deve alterar o `title`, e `owner` do projeto que possua o `id` igual ao `id` presente nos parâmetros da rota;

- **`DELETE /projects/:id`**: A rota deve deletar o projeto com o `id` presente nos parâmetros da rota;

## :cd: Pacotes instalados

A seguir segue uma lista dos pacotes instalados:

- [express](https://www.npmjs.com/package/express)
- [nodemon](https://www.npmjs.com/package/nodemon)
- [uuid](https://www.npmjs.com/package/uuid)

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
