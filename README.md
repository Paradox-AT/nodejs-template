# Node.js Template

A boilerplate Node.js project using TypeScript, organized for scalable application development.

## Features

- TypeScript support
- Modular folder structure (controllers, models, repositories, services, middlewares)
- Example routing
- Ready for testing and extension
- Uses pnpm for package management

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

## Contributing

Feel free to fork, submit issues, or open pull requests.

## License

MIT
