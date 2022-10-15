# My ticket.com test instalation instruction

**Tech Stack:**

* **Front-end Framework:** [React](https://reactjs.org/)

* **CSS Framework:** [Bootstrap](https://getbootstrap.com/)

* **Bundler:** [Vite](https://vitejs.dev/)

* **Package Manager:** [Yarn](https://yarnpkg.com/)

## Prerequisite

* Node 16.13.1 or higher
* Yarn Packages Manager

## Run Locally

Extract the `ticket.com.zip` file 

Go to the project directory
```bash
  cd ticket.com/ticket.com
```

Install dependencies

```bash
  yarn
```

Start the development server

```bash
  yarn dev
```

## Build

To build this project for production run

```bash
  yarn build
```

result is in `dist` directory

### ESLint + Prettier

We recommend to develop this project using [VSCODE](https://code.visualstudio.com/) with installed recommend extension below :

* dbaeumer.vscode-eslint (ESLint)
* esbenp.prettier-vscode (Prettier)

That allow us to get best experience for development.

### Project Directory

- `components/` - UI components that use in this project.
* `hooks/` - Custom hooks that use in this project.
* `types/` - TypeScript types + interfaces.
