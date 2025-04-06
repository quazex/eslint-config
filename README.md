# Custom ESLint Configuration

This package provides a custom ESLint configuration for TypeScript projects, ensuring consistent code quality and best practices.

## Features

- Predefined rules for TypeScript
- Optimized for NestJS and Node.js projects
- Support Stylistic for code formatting
- Extends some popular ESLint configurations
- Easy to integrate and customize

## Installation

```sh
npm install --save-dev @quazex/eslint-config
```

## Usage

Create an `.eslintrc.json` file in the root of your project and extend this configuration:

```json
{
    "extends": "@quazex/eslint-config"
}
```

Overrides

You can override any predefined rule in the config, for example:

```json
{
    "extends": "@quazex/eslint-config",
    "rules": {
        "init-declarations": "off",
    }
}
```

## License

MIT
