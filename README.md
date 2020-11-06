# private_npm

## 全局安装
```shell
npm i pm2 -g
npm i 
```

### 本地开发服务
```shell
npm run dev
```

### 服务器部署
```shell
npm i pm2 -g
npm i 
npm run pm2:start
```
### 启动 
```shell
npm run pm2:start 
```
### 关闭 
```shell
npm run pm2:stop
```

## 体验

### 下载
>无限制
> 存在本地缓存依赖或私有依赖优先使用本地,没有则默认代理npm org
```shell
npm i  --registry http://47.94.233.65:4000
```

### 发布
> 允许匿名发布，但需要在仓库名后加上 -test 例如 package.json -> name : xxxx-test

```shell
npm publish --registry http://47.94.233.65:4000
```