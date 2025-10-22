# Dynamic Slug

Dynamic Slug is a fullstack link shortener SaaS application built as a monorepo. It features a modern dashboard, authentication, analytics, and a robust backend API. The project is organized into two main packages: `backend` (NestJS API) and `ui` (React + Vite + Tailwind dashboard).

## Features

- User authentication and authorization
- Create, edit, and delete short links
- Analytics and statistics for each link
- Modern dashboard UI
- QR code generation
- RESTful API
- Monorepo structure with pnpm workspaces

## Tech Stack

- **Backend:** NestJS, TypeORM, MySQL, JWT, bcrypt
- **Frontend:** React, Vite, Tailwind CSS, Chart.js
- **Monorepo:** pnpm workspaces

## Getting Started

### Prerequisites
- Node.js (v18+ recommended)
- pnpm (v9+)
- MySQL database

### Installation

```bash
git clone https://github.com/IgnacioSotelo5/dynamic-slug.git
cd dynamic-slug
pnpm install
```

### Running the Backend

```bash
cd backend
cp .env.example .env # configure your environment variables
pnpm dev
```

### Running the Frontend

```bash
cd ui
pnpm dev
```

### Monorepo Scripts

From the root, you can run:

```bash
pnpm run dev # runs all dev scripts in packages
```

## Project Structure

```
dynamic-slug/
  backend/   # NestJS API
  ui/        # React dashboard
  package.json
  pnpm-workspace.yaml
  README.md
```

- See each package's README for more details and specific setup instructions.

## Roadmap
- [ ] Add e2e and unit tests
- [ ] Add custom domains
- [ ] Improve analytics dashboard
- [ ] Add billing and subscription support

## License
ISC
