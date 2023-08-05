# @13onthecode/typescript-config

<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/137921275/258572450-d0a2270e-45ad-4ed4-aed0-b5c0a2eea988.svg" width="100" height="100" align="right" alt="Typescript" />

[![Version](https://img.shields.io/npm/v/@13onthecode/typescript-config?color=1976d2&label=)](https://www.npmjs.com/package/@13onthecode/typescript-config)
[![License](https://img.shields.io/npm/l/@13onthecode/typescript-config?color=1976d2&label=)](LICENSE.md)

English | [简体中文](README.CN.md)

A versatile TypeScript configuration library that simplifies TypeScript setup using best practices, providing pre-configured tsconfig files for Node.js, React, and Vue projects

## Features
- Flexible configuration options to adapt to different project needs
- Integrated with best practices for accurate and reliable type checking
- Continuously maintained and updated, supporting the latest versions and features

## Prerequisites

- TypeScript version 5.0.0 or higher

## Install

```bash
npm install @13onthecode/typescript-config --save-dev
```

## Usage

To use the pre-configured tsconfig files, simply extend the configuration in your project's `tsconfig.json` file:

### Base

```json
{
  "extends": "@13onthecode/typescript-config/base"
}
```

### Node.js

```json
{
  "extends": "@13onthecode/typescript-config/node"
}
```

### React

```json
{
  "extends": "@13onthecode/typescript-config/react"
}
```

### Vue

```json
{
  "extends": "@13onthecode/typescript-config/vue"
}
```

## Packages

This package is a collection of the following shareable TypeScript configurations:

- [`@13onthecode/typescript-config-base`](https://github.com/13OnTheCode/typescript-config/tree/main/packages/base)
- [`@13onthecode/typescript-config-node`](https://github.com/13OnTheCode/typescript-config/tree/main/packages/node)
- [`@13onthecode/typescript-config-react`](https://github.com/13OnTheCode/typescript-config/tree/main/packages/react)
- [`@13onthecode/typescript-config-vue`](https://github.com/13OnTheCode/typescript-config/tree/main/packages/vue)

## License

[MIT](LICENSE.md) License &copy; 2023-PRESENT [13OnTheCode](https://github.com/13OnTheCode)
