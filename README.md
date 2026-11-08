# tutorial

React product CRUD tutorial app — a fork of
[prtcandido/tutorial](https://github.com/prtcandido/tutorial).

The app lists products and provides create, update and delete screens backed by
a REST API.

## Stack

- React 18 (Create React App)
- React Router
- Axios
- Sass

## Routes

| Route | Screen |
|---|---|
| `/` | Home |
| `/sobre` | About |
| `/produto` | Product list |
| `/produto/create` | Create product |
| `/produto/update/:id` | Update product |
| `/produto/delete/:id` | Delete product |

## Structure

```
├── src/
│   ├── Paginas/        # Home, Sobre, Produto, Layout
│   ├── Rotas.js        # route definitions
│   ├── App.js
│   └── index.js
└── public/
```

## Running

```bash
npm install
npm start     # development at http://localhost:3000
npm run build
```

The product screens call the `https://prtctec.com.br/api/produto` API.
