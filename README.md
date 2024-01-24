# Elysia with Bun runtime

## Getting Started
To get started with this template, simply paste this command into your terminal:
```bash
bun create elysia ./elysia-example
```

## Development
To start the development server run:
```bash
bun run dev
```

Open http://localhost:3000/ with your browser to see the result.


## Migrations

To make a migration run the next code:

```bash
bun run generate
bun -r esbuild-register src/db/migrate.ts
```