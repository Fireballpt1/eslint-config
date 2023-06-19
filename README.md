# Madeira Vip Travel ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint @mvt/eslint-config
```

2. Create/Open `.eslintrc.json` file extending the config:
```
{
  "extends": "@mvt/eslint-config/react"
  // "extends": "@mvt/eslint-config/node"
}
```

> You can also use a `.eslintrc.ts` instead of JSON if you prefer.
