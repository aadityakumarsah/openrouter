# 🚀 OpenRouter

A high-performance, scalable monorepo architecture for modern web applications. Built with speed, developer experience, and scalability in mind.

---

## 🏗️ Architecture

This project is a monorepo managed by **Turborepo** and powered by **Bun**. It separates concerns into specialized services and shared packages to ensure a robust and maintainable codebase.

### 📱 Applications (`/apps`)

- **`api-backend`**: High-performance API service built with **ElysiaJS**.
- **`primary-backend`**: Core business logic and background services.
- **`dashboard-frontend`**: A sleek, modern administration interface.

### 📦 Shared Packages (`/packages`)

- **`db`**: Centralized database schema, migrations, and ORM configurations.
- **`ui`**: Shared React component library for consistent design across frontends.
- **`typescript-config`**: Standardized TypeScript configurations.
- **`eslint-config`**: Enforced code quality and linting rules.

---

## 🛠️ Tech Stack

- **Runtime**: [Bun](https://bun.sh/)
- **Monorepo Tooling**: [Turborepo](https://turbo.build/)
- **Backend Framework**: [ElysiaJS](https://elysiajs.com/)
- **Frontend**: [Next.js](https://nextjs.org/) / [React](https://reactjs.org/)
- **Type Safety**: [TypeScript](https://www.typescriptlang.org/)
- **API Client**: [Eden](https://elysiajs.com/eden/overview.html) (End-to-end type safety)

---

## 🚦 Getting Started

### Prerequisites

Ensure you have [Bun](https://bun.sh/) installed on your machine.

```bash
curl -fsSL https://bun.sh/install | bash
```

### Installation

Clone the repository and install dependencies:

```bash
bun install
```

### Development

Run all applications in development mode:

```bash
bun dev
```

### Build

Compile all apps and packages for production:

```bash
bun run build
```

---

## 🤝 Contributing

1. Fork the project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">
  <br />
  Made with ❤️ by <b>Aaditya</b>
</div>
