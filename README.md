A development environment base on NervJS and TypeScript and created by create-react-app-typescript !

## 简介

本开发环境是基于 `React` 的官方脚手架 `create-react-app` 创建的，利用 `react-scripts-ts` 版本建立对 `typescript` 的支持。由于我们底层的框架需要用的是 `NervJS` 来兼容低版本的浏览器，慢慢的我们将替换 `React`。期望后续的探索能够顺利一些！！！

## 搭建

### 构建基于 React 的开发环境 

#### 利用 create-react-app 和 其扩展 react-scripts-ts 搭建基本框架

> create-react-app nervjs-typescript --scripts-version=react-scripts-ts

> cd nervjs-typescript

> yarn start

⚠️ 这里启动如果报类似如下的错误，请查看 https://github.com/wmonk/create-react-app-typescript/issues/274

```Shell
.../nervjs-typescript/node_modules/@types/react-dom/node_modules/@types/react/index.d.ts
(3631,13): Subsequent property declarations must have the same type.  Property 'a' must be of type 'DetailedHTMLProps<AnchorHTMLAttributes<HTMLAnchorElement>, HTMLAnchorElement>', but here has type 'DetailedHTMLProps<AnchorHTMLAttributes<HTMLAnchorElement>, HTMLAnchorElement>'.
```

#### 释放所有的配置信息

> npm run eject

到这里整个基于 React 的开发环境基本搭建完成！接下来，我们使用 `NervJS` 替换掉 `React`！



