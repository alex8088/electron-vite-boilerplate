# electron-app

![electron version](https://img.shields.io/github/package-json/dependency-version/alex8088/electron-vite-boilerplate/dev/electron)
![electron vite version](https://img.shields.io/github/package-json/dependency-version/alex8088/electron-vite-boilerplate/dev/electron-vite)
![electron builder version](https://img.shields.io/github/package-json/dependency-version/alex8088/electron-vite-boilerplate/dev/electron-builder)
![vite version](https://img.shields.io/github/package-json/dependency-version/alex8088/electron-vite-boilerplate/dev/vite)
![vue version](https://img.shields.io/github/package-json/dependency-version/alex8088/electron-vite-boilerplate/dev/vue)
![typescript version](https://img.shields.io/github/package-json/dependency-version/alex8088/electron-vite-boilerplate/dev/typescript)

> An Electron application with Vue3 and TypesSript

## Features

- **📁 Scaffolding - [create-electron](https://github.com/alex8088/quick-start/tree/master/packages/create-electron)**, scaffolding your project quickly
  - Currently supported framework: `Vue`, `React`, `Svelte`, `Solid`
- **🚀 Build - [electron-vite](https://github.com/alex8088/electron-vite)**, fast and easy-to-use build tool integrated with Vite 3
  - [Fast HMR](https://evite.netlify.app/guide/hmr-in-renderer.html)
  - [Hot Reloading](https://evite.netlify.app/guide/hot-reloading.html)
  - [Easy to Debug](https://evite.netlify.app/guide/debugging.html)
  - [Source code protection](https://evite.netlify.app/guide/source-code-protection.html) (compile to V8 bytecode to protect source code)
- **💡 Development - [electron-toolkit](https://github.com/alex8088/electron-toolkit)**, useful API, help you develop
- **📦 Pack - [electron-builder](https://www.electron.build)**, pre-configured to pack your app

---

- **📁 创建 - [create-electron](https://github.com/alex8088/quick-start/tree/master/packages/create-electron)**，快速构建项目
  - 目前支持的框架： `Vue`, `React`, `Svelte`, `Solid`
- **🚀 构建 - [electron-vite](https://github.com/alex8088/electron-vite)**，与 Vite 集成，快速且简单易用的构建工具
  - [热替换 HMR](https://cn-evite.netlify.app/guide/hmr-in-renderer.html)
  - [热重载](https://cn-evite.netlify.app/guide/hot-reloading.html)
  - [易于调试](https://cn-evite.netlify.app/guide/debugging.html)
  - [源代码保护](https://cn-evite.netlify.app/guide/source-code-protection.html)（编译为 V8 字节码以保护源代码）
- **💡 开发 - [electron-toolkit](https://github.com/alex8088/electron-toolkit)**，提供丰富实用 API，辅助开发
- **📦 打包 - [electron-builder](https://www.electron.build)**，预置打包配置，轻松完成打包

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) + [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

## Project Setup

### Install

```bash
$ npm install
```

### Development

```bash
$ npm run dev
```

### Build

```bash
# For windows
$ npm run build:win

# For macOS
$ npm run build:mac

# For Linux
$ npm run build:linux
```
