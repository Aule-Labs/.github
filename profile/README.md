# Aule Labs

Aule Labs is an independent AI research and engineering lab run by two students.

We're interested in understanding how artificial intelligence works, experimenting with new ideas, and building software. We learn through research, development, and experimentation, and write about our findings along the way.

Our work includes open-source projects, technical articles, and experiments in artificial intelligence.

## Projects

### keepalive-render

Keeps a free-tier [Render](https://render.com) service awake by pinging its `*.onrender.com` URL every 10 minutes, so the first visitor doesn't wait out a 50-second cold start. It asks for the URL once, then runs in the background — no config, no dependencies.

```bash
npx keepalive-render
```

Or install it once and run it whenever:

```bash
npm install -g keepalive-render
keepalive-render myapp
```

Source: https://github.com/Aule-Labs/keepAlive · npm: https://www.npmjs.com/package/keepalive-render
