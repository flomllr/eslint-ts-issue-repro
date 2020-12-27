Steps to reproduce:

1. Clone repo
2. `npm install``
3. `npx eslint src/App.tsx`
--> No errors are found, even though an undefined variable `world` is used.

(4. `npx eslint src/App.jsx` -> works as expected)
