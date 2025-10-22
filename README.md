# 🚀🔥 Node.js + TypeScript Template (pnpm + tsx)

A modern, lightning-fast Node.js starter template with TypeScript, pnpm, and tsx for zero-build backend development. Ready-to-use 🚀 scripts for start, dev, build plus ✅ type safety & IntelliSense

## ⚡ Features

- 💻 Node.js + TypeScript – Strongly typed backend development for scalability and maintainability.
- 📦 pnpm – Fast, disk-efficient package manager with deterministic installs.
- ⚡ tsx – Execute TypeScript directly without pre-compilation, supporting ESM modules.
- 🔄 Hot Reloading (optional): Integrated with tsx for seamless development experience.
- 🛠️ Dev Scripts – Ready-to-use commands for development, build, and production.
- ✅ Type Safety & IntelliSense – Full TypeScript support for robust code and better developer experience.
- ⚙️ Easy Setup – Minimal configuration; clone, install, and start coding immediately.

## Tech Stack

- Runtime: Node.js (v18+)
- Language: TypeScript
- Package Manager: pnpm
- Executor: ts-node

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

### Run the application(development)

```zsh
pnpm dev
```

### Run the application

```zsh
pnpm start
```

### Build and serve the application

```zsh
pnpm build
pnpm serve
```

## Scripts

- `pnpm dev` — Start the application in watch mode with tsx (recommended for development)
- `pnpm serve` — Run the compiled app from `dist/app.js` (for production)
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
