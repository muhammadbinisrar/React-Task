# React CRUD Sprint Solution

A Vite + React + Tailwind CSS app demonstrating all four CRUD operations with the DummyJSON Products API.

## Requirements
- Node.js 18 or newer
- npm
- Internet connection

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite (usually `http://localhost:5173`).

## Build check
```bash
npm run build
```

## API operations demonstrated
- **GET** `https://dummyjson.com/products?limit=12...` — loads products.
- **POST** `https://dummyjson.com/products/add` — adds a product.
- **PATCH** `https://dummyjson.com/products/:id` — updates a product.
- **DELETE** `https://dummyjson.com/products/:id` — deletes a product.

DummyJSON is a demo API. It simulates write operations rather than permanently saving them, so the React state is updated locally after successful responses.

## Suggested 45-minute demonstration
1. Run the app and show the product list loaded with GET.
2. Add a product and show the POST request in DevTools → Network.
3. Click Edit / PATCH, change the title or price, and save.
4. Delete a product and confirm it disappears.
5. In Network, filter by Fetch/XHR and show the request method and status for each operation.

## GitHub submission
Create a public repository on GitHub, then run these commands from this project folder:
```bash
git init
git add .
git commit -m "Complete React CRUD sprint"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
Replace the example remote URL with your own repository URL. Do not upload `node_modules`.
