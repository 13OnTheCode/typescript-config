# @13OnTheCode/Typescript-Config

<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/137921275/258572450-d0a2270e-45ad-4ed4-aed0-b5c0a2eea988.svg" width="100" height="100" align="right" alt="TypeScript" />

[![Version](https://img.shields.io/npm/v/@13onthecode/typescript-config?color=1976d2&label=)](https://www.npmjs.com/package/@13onthecode/typescript-config)
[![License](https://img.shields.io/npm/l/@13onthecode/typescript-config?color=1976d2&label=)](LICENSE.md)

[English](README.md) | 简体中文

一个通用的 TypeScript 配置库，它遵循最佳实践，为 Node.js、React 和 Vue 项目提供基础配置

## Features
- 遵循最佳实践，实现准确可靠的类型检查
- 灵活配置选项，适应不同项目需求
- 持续维护更新，支持最新的版本和特性

## Prerequisites

### TypeScript
- 版本 >= 5.0.0

## Install

```bash
npm install @13onthecode/typescript-config --save-dev
```

## Usage

要使用预配置的 tsconfig 文件，只需在项目的 `tsconfig.json` 文件中扩展配置:

#### Base

```json
{
  "extends": "@13onthecode/typescript-config/base"
}
```

#### Node.js

```json
{
  "extends": "@13onthecode/typescript-config/node"
}
```

#### React

```json
{
  "extends": "@13onthecode/typescript-config/react"
}
```

#### Vue

```json
{
  "extends": "@13onthecode/typescript-config/vue"
}
```

## Check Also
- [`@13OnTheCode/ESLint-Config`](https://github.com/13OnTheCode/eslint-config)

## License

[MIT](LICENSE.md) License &copy; 2023-PRESENT [13OnTheCode](https://github.com/13OnTheCode)
