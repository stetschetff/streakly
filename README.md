# streakly

Habit tracker grid built with Vue 3 composition API

## Usage

```bash
# open http://localhost:5173
# click a cell to toggle that day
```

## What it does

- Composition API + script setup
- GitHub-style contribution grid per habit
- Vite dev setup with hot reload
- State persisted to localStorage

## Install

```bash
npm install
npm run dev
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── dependabot.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── App.vue
│   ├── main.js
│   └── store.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── index.html
├── package.json
└── vite.config.js
```

## Development

```bash
npm install
```

## Changelog

- `0.1.1` - fix edge case in argument parsing
- `0.1.0` - first working version
