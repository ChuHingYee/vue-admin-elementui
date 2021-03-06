# 基于 element-ui 的后台管理系统

## 灵感来自

[PanJiaChen/vue-element-admin](https://github.com/PanJiaChen/vue-element-admin)
[(vue-element-admin 作者在最新的文章也提及到 Object.freeze 和函数式组件了,可以去学习一波)](https://juejin.im/post/5c92ff94f265da6128275a85?utm_source=gold_browser_extension#heading-22)。

[sendya/ant-design-pro-vue](https://github.com/sendya/ant-design-pro-vue)

## 功能特性

1. echart
2. 骨架屏组件
3. 卡片组件
4. 富文本（封装 tinymce5，不支持低版本浏览器）
5. 导出 excel
6. 视频播放（封装 vue-video-player）
7. 类浏览器标签栏
8. 权限指令
9. 数字格式化指令

## 安装

```shell
$ git clone https://github.com/ChuHingYee/elementui-admin-vue-boilerplate.git
$ npm install
```

## 运行

### 开发环境

```shell
$ npm run serve
```

### 生产环境

```shell
$ npm run build
```

### lint 检查并修复

```shell
$ npm run lint
```

### 单元测试

（暂无）

```shell
$ npm run test:unit
```

### 生成 element-ui 样式变量

路径：/src/styles/element-variables.scss

```shell
$ npm run theme:var
```

### 生成 element-ui 主题文件

路径：/src/theme

```shell
$ npm run theme
```
