## Backend Repo

The API repository required for this frontend application to run is available [here](https://github.com/Utsavojha2/entain-test-api). Please start the dev server on backend before running frontend.

## Application Tools

- React and SCSS (Configured with Webpack)
- [TypeScript](https://www.typescriptlang.org/)
- [Axios](https://www.npmjs.com/package/axios) (for API requests)

## Getting Started

First, run the development server:

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Integration and Unit tests

Jest and React Testing Library is used for testing components in isolation.

```bash
npm install
npm run test
```

## Cypress end-to-end test

To run cypress tests, follow the set of commands:

```bash
npm install
npm start
npx cypress open
```
