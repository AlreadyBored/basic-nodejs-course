# RS School NodeJS course

You can generate a new repository with the same directory structure and files as the [template repository](https://github.com/rolling-scopes-school/nodejs-course-template) using GitHub article: [ Creating a repository from a template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template).

**N.B**. Tasks for which the field *"Execute in"* wrirtten "template" should be implemented using the template, others - in the student's private repository.

---

## Tasks

### Task 1. Caesar cipher CLI tool

* Execute in: **private repository**
* [Description](./descriptions/caesar-cipher-cli-tool.md)
* [Cross-check criteria](./cross-check/caesar-cipher-cli-tool.md)

### Task 2. Testing

* Execute in: **private repository (from 1st task)**
* [Description](./descriptions/testing.md)
* [Cross-check criteria](./cross-check/testing.md)

### Task 3. In-memory CRU API

* Execute in: **private repository**
* [Description](./descriptions/simple-crud-api.md)
* [Cross-check criteria](./cross-check/simple-crud-api.md)

### Task 4. REST Service
* Execute in: **template**
* [Description](./descriptions/express-rest-service.md)
* [Cross-check criteria](./cross-check/express-rest-service.md)

### Task 5. Typescript basics

* Execute in: **template**
* [Description](./descriptions/typescript-basics.md)
* [Cross-check criteria](./cross-check/typescript-basics.md)

### Task 6. Logging & Error Handling

* Execute in: **template**
* [Description](./descriptions/logging-error-handling.md)
* [Cross-check criteria](./cross-check/logging-error-handling.md)

### Task 7. Docker basics

* Execute in: **template**
* [Description](./descriptions/docker-basics.md)
* [Cross-check criteria](./cross-check/docker-basics.md)

### Task 8. PostgreSQL & Typeorm

* Execute in: **template**
* [Description](./descriptions/postgresql-typeorm.md)
* [Cross-check criteria](./cross-check/postgresql-typeorm.md)

### Task 9. Authentification & JWT

* Execute in: **template**
* [Description](./descriptions/authentification-jwt.md)
* [Cross-check criteria](./cross-check/authentification-jwt.md)

### Task 10. NestJS

* Execute in: **template**
* [Description](./descriptions/nestjs.md)
* [Cross-check criteria](./cross-check/nestjs.md)

---

## Hints

>  ### **How to get update from [template](https://github.com/rolling-scopes-school/nodejs-course-template/tree/master)**
>  1. Set VSCode as a default GIT editor (it's not mandatory)
>    ```bash
>      git config --global core.editor "code --wait"
>    ```
>  2. Commit current changes
>  3. Add template as the remote repository
>    ```bash
>      git remote add template https://github.com/rolling-scopes-school/nodejs-course-template.git
>    ```
>  4. Apply changes from template
>    ```bash
>      git pull template master --allow-unrelated-histories
>    ```
>  5. Apply all your changes
>    ```bash
>      git checkout --ours ':!node_modules'
>    ```
>  6. Apply all changes
>    ```bash
>      git checkout --theirs .
>    ```
>  7. Save changes
>    ```bash
>      git add .
>    ```
>  8. Continue merge
>    ```bash
>      git commit
>    ```
>  9. Close VSCode tab with commit message. If  default editor wasn't changed - quit VIM via `:qa`