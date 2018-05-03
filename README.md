# Vitaliy's ESLint Config

Sharable code style, overrides [AirBnB code style
guide](https://github.com/airbnb/javascript) with my preferences.

## Install

```bash
npm i --save-dev eslint-config-vit
```

## Usage

Add to your ESLint config, according to environment

**Browser:**

```json
{
  "extends": "vit/browser"
}
```

**Browser ESNext:**

```json
{
  "extends": "vit/browserNext"
}
```

**Node:**

```json
{
  "extends": "vit/node"
}
```
