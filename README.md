# @jihchi/vite-plugin-rescript

[![Workflows - CI][workflows-ci-shield]][workflows-ci-url]
[![npm package][npm-package-shield]][npm-package-url]
[![bundlephobia size][bundlephobia-size-shield]][bundlephobia-size-url]
![npm download per month][npm-download-shield]
[![npm license][npm-licence-shield]](./LICENSE)

## Getting Started

> If you are looking for a template to quickly start a project using Vite, ReScript and React, take a look at [vitejs-template-react-rescript](https://github.com/jihchi/vitejs-template-react-rescript), the template depends on this plugin.

### npm

```sh
npm i -D @jihchi/vite-plugin-rescript
```

### yarn

```sh
yarn add -D @jihchi/vite-plugin-rescript
```

Configure your vite plugin in `vite.config.ts`:

```js
import { defineConfig } from 'vite';
import createReScriptPlugin from '@jihchi/vite-plugin-rescript';

export default defineConfig({
  plugins: [createReScriptPlugin()],
});
```

[workflows-ci-shield]: https://github.com/jihchi/vite-plugin-rescript/actions/workflows/main.yml/badge.svg
[workflows-ci-url]: https://github.com/jihchi/vite-plugin-rescript/actions/workflows/main.yml
[npm-package-shield]: https://img.shields.io/npm/v/@jihchi/vite-plugin-rescript
[npm-package-url]: https://www.npmjs.com/package/@jihchi/vite-plugin-rescript
[npm-download-shield]: https://img.shields.io/npm/dm/@jihchi/vite-plugin-rescript
[npm-licence-shield]: https://img.shields.io/npm/l/@jihchi/vite-plugin-rescript
[bundlephobia-size-shield]: https://img.shields.io/bundlephobia/min/@jihchi/vite-plugin-rescript
[bundlephobia-size-url]: https://bundlephobia.com/package/@jihchi/vite-plugin-rescript
