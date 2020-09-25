<p align="right">
  <a href="README.en.md">🇺🇸</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.md">🇧🇷</a>&nbsp;&nbsp;&nbsp;
</p>

<img alt="GoStack" src=./src/assets/header-bootcamp.png />

<h3 align="center">
  Node.js Concepts
</h3>

<p align="center">
  <a href="#🚀-about-the-application">About the application</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#💿-required-packages">Required packages</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#📝-licence">Licence</a>
</p>

<img alt="Insomnia" src=./src/assets/screen-insomnia.gif />

## 🚀 About the application

A simple application in Node.js!

This is an application to storage projects of your portfolio, that allow you to create, to list, update and remove projects.

### Application Routes

In the index.js file:

- **`POST /projects`**: The route must receive `title` and `owner` inside of the request body. When registering a new project, it must be stored inside an object in the following format: `{ id: "uuid", title: 'Project X', owner: 'Bruno' }`;

- **`GET /projects`**: The route that lists all projects;

- **`PUT /projects/:id`**: The route should change the `title` and `owner` of the project that has the` id` equal to the `id` present in the route parameters;

- **`DELETE /projects/:id`**: The route must delete a project with the `id` present in the route parameters;

## 💿 Required packages

The following is a list of the packages needed for the application (Using [yarn](https://yarnpkg.com/)):

- yarn add [express](https://www.npmjs.com/package/express)
- yarn add [nodemon](https://www.npmjs.com/package/nodemon) -D
- yarn add [uuid](https://www.npmjs.com/package/uuid)

## 📝 Licence

This project is under license from MIT. See the archive [LICENSE](LICENSE) to more details.