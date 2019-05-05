# mfv-cli-service

> cli-service for micro-frontends-vue

## 定制版 [cli-service](https://cli.vuejs.org/)

修改 `--target lib` 模式下输出文件的格式：

1. 入口文件为 `main.js`
2. 其他文件增加 `chunkhash` 防缓存

## CHANGELOG

### @2019-05-05

同步自 vue-cli-service@3.7.0

1. `./lib/commands/build/resolveLibConfig.js`
   修改 lib 打包输出结果；输出文件添加 hash 防缓存
2. 替换 command 命令 vue-cli-service 为 mfv-cli-service
3. 修改 package.json files 字段
