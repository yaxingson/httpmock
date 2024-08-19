# node-http-server

## 应用

异步驱动原理(依赖于libuv库): 事件循环

架构设计规范:

- RESTful
- RPC

> 洋葱模型

多进程解决方案:

```js
const cluster = require('node:cluster')
const numCPUs = require('node:os').availableParallelism()

```

## 部署

### docker

> 多阶段构建

### pm2


## 监控和告警

```sh
npm i heapdump

```

### memory

### cpu

> 过载保护（熔断）

```sh
ps -p 5612 -o pid,rss,vsz,pcpu,comm

```


## 日志

```sh
npm i log4js winston

```

## 数据库

> 缓存
