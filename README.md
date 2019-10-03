TypeScript Webpack Font Loader Demo
=======================================

这里以google的Bitter为例。好在有人提供了`@openfonts/bitter_latin`这个包，不然需要自己处理很多东西。

在webpack config中，需要使用`url-loader`来处理对字体的解析，它会生成一个url来提供字体文件的载入。

注意：通常每种字段都有多种格式的文件，以兼容不同的浏览器。不过现在基本上都支持`woff`或者`woff2`，所以只提供这一种就可以了。

```
npm install
npm run demo
```
