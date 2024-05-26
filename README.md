# To-Do-App created by Dániel Juhász

This is a monorepo collecting the contents of [to-do-app-frontend](https://github.com/DanShepherd27/to-do-app-frontend) and [to-do-app-backend](https://github.com/DanShepherd27/to-do-app-backend) repos.

## Release

Current version: v1.0

# Backend

Created with: NestJS, TypeScript

## Installation

1. Create PostgreSQL database (e.g. with pgAdmin)

2. Enter backend directory

```bash
$ cd backend
```

3. Place your database credentials in a .env file (create it according to .env.sample)

4. Install npm packages

```bash
$ npm install
```

5. Run the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run build
$ npm run start:prod
```

Open [http://localhost:3000/api](http://localhost:3000/api) with your browser for Swagger documentation of endpoints.

# Frontend

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

1. Make sure you have your .env.production set similar to .env.sample

2. Enter frontend directory

```bash
$ cd frontend
```

3. Install dependencies, build and run

```bash
npm install
npm run build
npm start
```

Open [http://localhost:4000](http://localhost:4000) with your browser to see the result.

## Notes

Commit messages are written according to: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

Styled using [Styled Components](https://styled-components.com/)
