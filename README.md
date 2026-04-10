# generator-babel-plugin [![Node.js Package](https://github.com/tolerious/generator-babel-plugin/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/tolerious/generator-babel-plugin/actions/workflows/npm-publish.yml)
使用Yeoman来创建babel plugin.
代码fork自[generator-babel-plugin](https://github.com/thejameskyle/generator-babel-plugin)，
原仓库经过测试，在本地无法运行了，故此fork了项目进行了修改。 

## 用法

**全局安装Yeoman**

```shell
$ npm i -g yo
$ npm i -g generator-babel-plugins
```

**运行generator**

```shell
$ yo babel-plugins
```

如果你想在测试中创建额外的fixtures

```shell
$ yo babel-plugins:fixture name-of-fixture
```

为了更好的理解Babel插件的开发，强烈建议阅读[babel plugin handbook](https://github.com/thejameskyle/babel-handbook/blob/master/translations/en/plugin-handbook.md)。

同时我也提供了[中文翻译改进版](https://babel.frontend.fan/user-handbook)，针对原版中的排版问题以及过时的描述予以更正。

## License

MIT
