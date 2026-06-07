# Extension Project — Web Platform for the Cooperative

This repository was organized as an initial structure for the **Doce Sabor Digital** project, separating backend, frontend, and documentation.

## Screenshots

![Doce Sabor Digital preview](screenshot-1.svg)

![Order flow concept](screenshot-2.svg)

## Structure

```text
doce-sabor-digital/
├── backend/
│   ├── src/
│   ├── package.json
│   └── README.md
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── README.md
├── docs/
│   ├── summary-report.md
│   └── images/
├── screenshot-1.svg
├── screenshot-2.svg
├── .gitignore
├── README.md
└── LICENSE
```

## Objective

Build a web platform to support the cooperative with digital processes such as:

- product and service promotion;
- customer contact;
- organization of institutional information;
- future evolution toward administrative features.

## Suggested Next Steps

1. Implement the API in `backend/src`.
2. Create the user interface in `frontend/src`.
3. Document decisions and progress in `docs/summary-report.md`.
4. Standardize scripts such as `dev`, `build`, and `test` in both backend and frontend.

## Getting Started

### Backend

```bash
cd doce-sabor-digital/backend
npm install
npm run dev
```

### Frontend

```bash
cd doce-sabor-digital/frontend
npm install
npm run dev
```

> Note: the current files are a starting point. Adjust dependencies and scripts according to the framework selected for implementation.
