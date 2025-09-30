# Node.js Template

A boilerplate Node.js project using TypeScript, organized for scalable application development.

## Features

- TypeScript support
- Typescript best practices enforced
- Uses pnpm for faster package management

## Project Structure

```
.gitignore
.nvmrc
.vscode/
LICENSE
README.md
app.ts
package.json
pnpm-lock.yaml
pnpm-workspace.yaml
tsconfig.json
```

## Getting Started

### Prerequisites

- Node.js (v22+ recommended)
- pnpm (https://pnpm.io/)

### Install dependencies

```zsh
pnpm install
```

### Run the application

```zsh
pnpm start
```

### Build the application

```zsh
pnpm build
```

## Scripts

- `pnpm start` — Start the application in watch mode with tsx (recommended for development)
- `pnpm serve` — Build and run the compiled app from `dist/app.js` (for production)
- `pnpm build` — Compile TypeScript to JavaScript

## Using This Repository as a Template

You can use this repository as a template for your own Node.js projects:

1. On GitHub, click the "Use this template" button at the top of the repository page.
2. Create a new repository from the template.
3. Clone your new repository:
   ```zsh
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
4. Install dependencies:
   ```zsh
   pnpm install
   ```
5. Start building your project!

## Contributing

Feel free to fork, submit issues, or open pull requests.

## License

MIT
