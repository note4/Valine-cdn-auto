# Valine-cdn-auto Valine自动cdn版本

## cdn 地址

- <https://cdn.jsdelivr.net/npm/valine-cdn-auto@1.5.3/dist/Valine.min.js>
- <https://unpkg.com/valine-cdn-auto@1.5.3/dist/Valine.min.js>

## av-min 根据 valine 域名自动读取CDN

如果 valine.min.js 域名 为 cdn.jsdelivr.net 使用 `https://cdn.jsdelivr.net/npm/leancloud-storage@3/dist/av-min.js`。

如果 valine.min.js 域名不是 cdn.jsdelivr.net 使用 `https://unpkg.com/leancloud-storage@3/dist/av-min.js`。

例如：使用 `https://unpkg.com/valine-cdn-auto@1.5.3/dist/Valine.min.js` 请求的av-min.js 会是 `https://unpkg.com/leancloud-storage@3/dist/av-min.js`

***

> 由于某些原因，`src目录`将从`v1.4.0`后暂停更新.  
  For some reason, the `src directory` will be suspended from updating after `v1.4.0`.

<img src='./src/assets/valine.png' width='200' align="right" />

# Valine

[![version](https://img.shields.io/github/release/xCss/Valine.svg?style=flat-square)](https://github.com/xCss/Valine/releases) [![npm downloads](https://img.shields.io/npm/dm/valine.svg?style=flat-square)](https://www.npmjs.com/package/valine) [![build](https://img.shields.io/circleci/project/github/xCss/Valine/master.svg?style=flat-square)](https://circleci.com/gh/xCss/Valine) [![donate](https://img.shields.io/badge/$-donate-ff69b4.svg?maxAge=2592000&style=flat-square)](#donate)  

> A fast, simple & powerful comment system.  
------------------------------
**[View Documentation](https://valine.js.org)**

## Features
- High speed.
- Safe by default.
- No server-side implementation.
- Support for full markdown syntax.
- Simple and lightweight.

See the [Quick start](https://valine.js.org) for more details.

## Contributors
- [Contributors](https://github.com/xCss/Valine/graphs/contributors)

## License
[GPL-2.0](https://github.com/xCss/Valine/blob/master/LICENSE)
