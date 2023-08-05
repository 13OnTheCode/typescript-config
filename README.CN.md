# @13onthecode/typescript-config

<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/137921275/258572450-d0a2270e-45ad-4ed4-aed0-b5c0a2eea988.svg" width="100" height="100" align="right" alt="Typescript" />

[![Version](https://img.shields.io/npm/v/@13onthecode/typescript-config?color=1976d2&label=)](https://www.npmjs.com/package/@13onthecode/typescript-config)
[![License](https://img.shields.io/npm/l/@13onthecode/typescript-config?color=1976d2&label=)](LICENSE.md)

[English](README.md) | 简体中文

一个通用的 TypeScript 配置库，使用最佳实践简化你的 TypeScript 设置，为 Node.js、React 和 Vue 项目提供预先配置的 tsconfig 文件

## Features
- 灵活的配置选项，适应不同项目需求
- 集成了最佳实践，实现准确可靠的类型检查
- 持续维护和更新，支持最新的版本和特性

## Prerequisites

- TypeScript 版本需要 5.0.0 或更高

## Install

```bash
npm install @13onthecode/typescript-config --save-dev
```

## Usage

要使用预配置的 tsconfig 文件，只需在项目的 `tsconfig.json` 文件中扩展配置:

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

该包是以下共享 TypeScript 配置包的集合：

- [`@13onthecode/typescript-config-base`](https://github.com/13OnTheCode/typescript-config/tree/main/packages/base)
- [`@13onthecode/typescript-config-node`](https://github.com/13OnTheCode/typescript-config/tree/main/packages/node)
- [`@13onthecode/typescript-config-react`](https://github.com/13OnTheCode/typescript-config/tree/main/packages/react)
- [`@13onthecode/typescript-config-vue`](https://github.com/13OnTheCode/typescript-config/tree/main/packages/vue)

## License

[MIT](LICENSE.md) License &copy; 2023-PRESENT [13OnTheCode](https://github.com/13OnTheCode)
