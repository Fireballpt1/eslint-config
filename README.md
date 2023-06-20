# ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint eslint-config-leonardo-santos
```

2. Create/Open `.eslintrc.json` file extending the config:
```
{
  "extends": "eslint-config-leonardo-santos/react"
  // "extends": "eslint-config-leonardo-santos/node"
}
```

> You can also use a `.eslintrc.ts` instead of JSON if you prefer.
