# Dynamic Slug Backend

This is the backend API for Dynamic Slug, a fullstack link shortener SaaS. Built with NestJS, TypeORM, and MySQL, it provides authentication, link management, analytics, and a RESTful API for the dashboard frontend.

## Features
- User authentication (JWT)
- Create, edit, delete short links
- Analytics for each link
- QR code generation
- RESTful API

## Tech Stack
- NestJS
- TypeORM
- MySQL
- JWT, bcrypt

## Getting Started

### Prerequisites
- Node.js (v18+)
- pnpm
- MySQL database

### Installation
```bash
cd backend
pnpm install
cp .env.example .env # configure your environment variables
```

### Running the Server
```bash
pnpm dev
```

API will be available at `http://localhost:3001` (or your configured port).

## Scripts
- `pnpm dev` - Start in development mode
- `pnpm build` - Build the project
- `pnpm test` - Run tests

## License
ISC
