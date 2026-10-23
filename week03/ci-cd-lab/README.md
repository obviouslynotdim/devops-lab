# ci-cd-lab

A small Express 5 app with a GitHub Actions CI pipeline (ESLint, Mocha tests, c8 coverage).

## Requirements

- Node.js 24+
- Yarn 4 (via Corepack: `corepack enable`)

## Commands

```bash
yarn install    # install dependencies
yarn start      # run on http://localhost:3000 (or $PORT)
yarn lint       # ESLint
yarn test       # Mocha tests
yarn coverage   # tests with c8 coverage; HTML report in coverage/
```

## Endpoints

| Method | Path | Response |
|--------|------|----------|
| GET    | `/`  | `Hello, GitHub Actions!` |
