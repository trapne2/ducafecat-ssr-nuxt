# ducafecat-ssr-nuxt

> 基于 `Nuxt.js` 打造企业级项目模板

## todo

- [ ] ** 通用模块 **
    - [ ] 模块化 `store`
    - [ ] 数据通讯封装 `server` `client`
    - [ ] 数据代理转发
    - [ ] 支持 `sass` 样式
    - [ ] 支持 `svg` 图标编译
    - [ ] `ie8` 兼容 `polyfill`
    - [ ] 开启 `gzip`
    - [ ] 网站图标 `favicon`
    - [x] 部署 `pm2`

- [ ] ** 业务模块 **
    - [ ] 安全认证 `token` 离线登录
    - [ ] 路由权限控制

- [ ] ** UI组件 **
    - [ ] 默认载入 `normalize`
    - [ ] 页面载入进度条
    - [ ] 错误页面 `404` `500`

## Build Setup

``` bash
# install pm2
$ sudo npm install -g pm2

# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# "start": "nuxt start",

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).
