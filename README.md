# egg-direct

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/egg-direct.svg?style=flat-square
[npm-url]: https://npmjs.org/package/egg-direct
[travis-image]: https://img.shields.io/travis/eggjs/egg-direct.svg?style=flat-square
[travis-url]: https://travis-ci.org/eggjs/egg-direct
[codecov-image]: https://img.shields.io/codecov/c/github/eggjs/egg-direct.svg?style=flat-square
[codecov-url]: https://codecov.io/github/eggjs/egg-direct?branch=master
[david-image]: https://img.shields.io/david/eggjs/egg-direct.svg?style=flat-square
[david-url]: https://david-dm.org/eggjs/egg-direct
[snyk-image]: https://snyk.io/test/npm/egg-direct/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/egg-direct
[download-image]: https://img.shields.io/npm/dm/egg-direct.svg?style=flat-square
[download-url]: https://npmjs.org/package/egg-direct

eggjs 路由去中心化插件。

## 依赖说明

### 依赖的 egg 版本

egg-direct 版本 | egg 2.x | egg 1.x
--- | --- | ---
0.x | 😁 | ❌

### 依赖的插件

- egg-core （这个一般都会被集成在egg里面，不需要单独安装。）

## 开启插件

```js
// config/plugin.js
exports.direct = {
  enable: true,
  package: 'egg-direct',
};
```

## 使用场景

- Why and What: 描述为什么会有这个插件，它主要在完成一件什么事情。
尽可能描述详细。
- How: 描述这个插件是怎样使用的，具体的示例代码，甚至提供一个完整的示例，并给出链接。

## 详细配置

请到 [config/config.default.js](config/config.default.js) 查看详细配置项说明。

## 单元测试

```
$ npm run test
```

## 提问交流

请到 [egg-direct issues](https://github.com/lisniuse/egg-direct/issues) 异步交流。

## License

[MIT](LICENSE)
