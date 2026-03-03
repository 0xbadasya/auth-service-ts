# auth-service-ts

## Run locally

```bash
npm install
npm run dev
```

Health check:

- `GET http://localhost:3000/health`

## Build and run

```bash
npm run build
npm start
```

## CI

GitHub Actions workflow `CI` runs on push/PR for `dev` and `main` and executes:

- `npm ci`
- `npm run lint`
- `npm run build`
