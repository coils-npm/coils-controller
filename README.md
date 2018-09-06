### Install
```
$ npm i coils-controller -S
```

该组件依赖于 `koa`, `koa-router`


组件返回  CoilsController


Coils 调用
```
application.use(CoilsController)
```
将自动加载 `app/middleware`下的中间件,按文件字典顺序加载

实例化`require('app/controllers'')`的所有Controller