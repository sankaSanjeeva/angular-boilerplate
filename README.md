<p align="center">
  <img src="https://api.iconify.design/logos:angular-icon.svg" alt="Angular brand" width="100" height="100"/>
</p>

<h1 align="center">Angular Boilerplate</h1>

<br>

<p align='center'>
  <a href="https://angularboilerplate.vercel.app/">Live site (Demo)</a>
</p>

<br>

<p align='center'>
  <strong>English</strong> |
  <a href="https://github.com/juanmesa2097/angular-boilerplate/blob/main/README.es-CO.md">Español</a>
</p>

<br>

This is a highly opinionated Angular starter designed to keep up with the latest Angular features and best practices. It provides the bare minimum features necessary to remove unnecessary overhead and maintain flexibility and scalability. The goal is to maintain a lightweight codebase while providing a robust set of features. This approach allows other developers to choose the technologies they want to use, such as UI component libraries, state management, server-side rendering (SSR), etc. By keeping the boilerplate flexible, developers can easily customize the code and adapt it to their unique project needs.

## ⚗️ Features

- [Angular 16](https://angular.io/docs)
- [PNPM](https://pnpm.io/), [esbuild](https://esbuild.github.io/)
- [Standalone components](https://angular.io/guide/standalone-components)
- [Signals](https://angular.io/guide/signals)
- [Lazy loading](https://angular.io/guide/lazy-loading-ngmodules)
- [PWA](https://angular.io/guide/service-worker-getting-started)
- [I18n](https://ngneat.github.io/transloco/)
- [TailwindCSS](https://tailwindcss.com/)
- OS/Light/Dark themes
- Lightweight, fast, and built using state-of-the-art technology.

## ✅ Ready-to-use

### UI Frameworks

- [TailwindCSS](https://tailwindcss.com/)

### Icons

- [Iconify](https://iconify.design) - use icons from any icon sets [🔍Icônes](https://icones.netlify.app/)
- [Pure CSS icons via @iconify/tailwind](https://docs.iconify.design/usage/css/tailwind/)

### Add-ons

- <https://github.com/ngneat/transloco>
- <https://github.com/tailwindlabs/tailwindcss>
  - <https://github.com/tailwindlabs/tailwindcss-aspect-ratio>
  - <https://github.com/tailwindlabs/tailwindcss-forms>
  - <https://github.com/tailwindlabs/tailwindcss-typography>
  - <https://github.com/tailwindlabs/prettier-plugin-tailwindcss>
- <https://github.com/iconify/iconify>
  - <https://github.com/iconify/iconify/tree/main/plugins/tailwind>

## ⚙ Prerequisites

- Node.js ([^16.14.0 || ^18.10.0](https://angular.io/guide/versions)): <https://nodejs.org/en/>
- PNPM: <https://pnpm.io/es/>
- Docker (optional): <https://www.docker.com/>

## 🏹 Start development

> **Note:**
> You have three options to start a new project based on this template:
>
> 1. Create a new GitHub repository from this template.
> 2. Clone this repository to start with a clean git history.
> 3. Scaffold the project on StackBlitz.

### Using the GitHub template

[Create a repo from this template on GitHub](https://github.com/juanmesa2097/angular-boilerplate/generate).

---

### Cloning the repository locally

```sh
npx degit juanmesa2097/angular-boilerplate my-app && cd my-app && ./scripts/rename_project.sh my-app
```

### Install dependencies

```sh
pnpm install # run `pnpm install -g pnpm` if you don't have pnpm installed
```

### Run project

```sh
pnpm start
```

---

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://analogjs.org/new)

## 📝 Checklist

Please review this checklist and modify it as necessary to meet your project requirements.

- [ ] Run the `./scripts/rename_project.sh` script to rename the project.
- [ ] Change the title in `src/index.html` and the favicon in `src/favicon.ico` to match your project.
- [ ] Decide whether to continue using [simple-git-hooks](https://github.com/toplenboren/simple-git-hooks) and [lint-staged](https://github.com/okonet/lint-staged) for your project.
- [ ] Clean up the README file to provide clear instructions about your project.
- [ ] Modify the pages in the project to meet your specific requirements.

## 📦 Deploy to Vercel

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/juanmesa2097/angular-boilerplate)

## 📦 Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/juanmesa2097/angular-boilerplate)

## 🐳 Docker

Create an image of the project.

```sh
docker build -t angular-boilerplate:latest .
```

Run the image of the project.

```sh
docker run --rm -p 8080:80 -d angular-boilerplate:latest
```

## 🧙‍♂️ Commands

| Command         | Description                                              | npm                     | yarn                     | pnpm                     |
| --------------- | -------------------------------------------------------- | ----------------------- | ------------------------ | ------------------------ |
| `start`         | Starts the development server                            | `npm start`             | `yarn start`             | `pnpm run start`         |
| `build`         | Builds the production code                               | `npm run build`         | `yarn build`             | `pnpm run build`         |
| `watch`         | Builds the production code and watches for changes       | `npm run watch`         | `yarn run watch`         | `pnpm run watch`         |
| `test`          | Runs the unit tests                                      | `npm run test`          | `yarn run test`          | `pnpm run test`          |
| `test:headless` | Runs the unit tests in headless mode                     | `npm run test:headless` | `yarn run test:headless` | `pnpm run test:headless` |
| `lint`          | Runs the linter                                          | `npm run lint`          | `yarn run lint`          | `pnpm run lint`          |
| `lint:fix`      | Runs the linter and fixes any linting errors             | `npm run lint:fix`      | `yarn run lint:fix`      | `pnpm run lint:fix`      |
| `lint:staged`   | Runs the linter on staged files                          | `npm run lint:staged`   | `yarn run lint:staged`   | `pnpm run lint:staged`   |
| `stylelint`     | Runs the style linter                                    | `npm run stylelint`     | `yarn run stylelint`     | `pnpm run stylelint`     |
| `stylelint:fix` | Runs the style linter and fixes any style linting errors | `npm run stylelint:fix` | `yarn run stylelint:fix` | `pnpm run stylelint:fix` |
| `format`        | Formats the code with prettier                           | `npm run format`        | `yarn run format`        | `pnpm run format`        |
