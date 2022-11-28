<p align="center">
  <img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" />
</p>

</div>
<div align="center">
  <h1>Microservice</h1>
  <strong>Microservice structure with NodeJS and MongoDB</strong>
</div>

</br>

## Introduction

Project introduction.

## Technologies

<section align="center" sytle="padding-top: 20%; padding-bottom: 20%">
    <img align="left"   style="float: left; margin-right: 2px;" alt="MongoDB" width="30px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/01.MongoDB.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="NestJS" width="30px" src="https://nestjs.com/img/logo-small.svg" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="NodeJS" width="30px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/04.NodeJS.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="TypeScript" width="30px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/28.TypeScript.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Git" width="30px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/17.Git.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Postman" width="30px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/22.Postman.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="GitHub" width="30px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/18.GitHub.png" />
    <img align="left"   style="float: left; margin-right: 2px;" alt="Visual Studio Code" width="30px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/19.VSCode.png" />
    <img align="left"   style="float: left; margin-right: 4px;" alt="Terminal" width="30px" src="https://github.com/carlos-garcia-dev/carlos-garcia-dev-images/blob/master/images/png/20.Terminal.png" />
</section>

</br>

## Project

Project Description

</br>

<!-- <details open="open">
<summary>Table of Contents</summary>

- [About](#about)
  - [Built With](#built-with)
</details> -->

## Microservice

<!-- [Image]() -->

Each module was focused in one area of the language.

### Server - Endpoints

|  Method   | Path       | Description                            |
| :-------: | ---------- | -------------------------------------- |
|  **Get**  | /users/    | Request all users from a Database.     |
|  **Get**  | /users/:id | Request an specific user.              |
| **Patch** | /users/:id | Update an specific user.               |
| **Post**  | /users/    | Send the request to create a new user. |

### Server - Structure

Description of the server functionalities.

```bash
  │ 
  ├── nest-cli.json
  ├── package-lock.json
  ├── package.json
  ├── 📁 src
  │   ├── app.controller.spec.ts
  │   ├── app.controller.ts
  │   ├── app.module.ts
  │   ├── app.service.ts
  │   ├── main.ts
  │   └── 📁 users
  │       ├── 📁 dto
  │       │   ├── create-user.dto.ts
  │       │   └── update-user.dto.ts
  │       ├── 📁 schemas
  │       │   └── user.schema.ts
  │       ├── users.controller.ts
  │       ├── users.module.ts
  │       ├── users.repository.ts
  │       └── users.service.ts
  ├── 📁 test
  │   ├── app.e2e-spec.ts
  │   └── jest-e2e.json
  ├── tsconfig.build.json
  └── tsconfig.json
```

## Links

1. [Microservices-Guide](https://www.martinfowler.com/microservices/) : Article of Martin Fowler about microservices work and scale.
