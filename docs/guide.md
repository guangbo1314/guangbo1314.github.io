# 开始使用

这是文档站点的第一页。之后的文章都放在 `docs/` 目录下，用标准 Markdown 编写。

## 写作约定

- 大标题用 `#`，例如 `# Q1：为什么收费`
- 超链接用 `[显示文字](链接地址)`，例如 `[示例页面](/guide)`
- 普通文字直接书写

## 本地预览

```bash
npm install
npm run docs:dev
```

浏览器打开终端提示的地址即可预览。

## 构建

```bash
npm run docs:build
```

构建产物位于 `docs/.vitepress/dist`。
