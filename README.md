# Bun Project Template
This template is built for full-stack apps where frontend and backend live in the same codebase. The src/client folder holds the client-side TypeScript, which gets compiled to JavaScript in dist/ for browsers. Meanwhile, all other TypeScript files stay as TS and run directly from dist/ on the backend using Bun.

Perfect for projects like browser games or complex web apps that need tight integration between client and server code without juggling separate repos or build systems.

If your app is strictly backend or simple frontend-only, this might be more than you need — but if you want a unified, clean workflow for full-stack TypeScript with Bun and Express, this template has your back.


If you run the command it will automaticaly build the necessary scripts from src to dist, converting all the client side code to js and keeping all the server side code as ts.

```bash
bun run dev
```

To have hot realoading run

```bash
bun run dev-watch
```

To install dependencies:

```bash
bun install
```


