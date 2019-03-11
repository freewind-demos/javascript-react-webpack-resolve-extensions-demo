JavaScript React Webpack "resolve" "extensions" Demo
====================================================

当我们在webpack.config.js中的指定了resolve的extensions中包含了"jsx"时，import一个jsx文件时，可以省掉后缀，
写成`from './hello'`而不是`from './hello.jsx`。

注意：`.js`的extension也不能少，否则不能处理js文件的导入了。

```
npm install
npm run demo
```

