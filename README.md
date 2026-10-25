# 小棋星乐园

一个为小学阶段孩子设计的棋类启蒙学习平台，包含：

- 五子棋：5 个成长阶段与连续进攻练习
- 中国象棋：6 个启蒙阶段、棋子走法与人机对局
- 围棋：6 个启蒙阶段、气与提子练习和 9 路对局

所有内容均可直接在浏览器中使用，不需要安装软件。学习进度保存在当前设备的浏览器中。

## 在线使用

- GitHub Pages：<https://handsun85s.github.io/little-chess-star/>
- 备用地址：<https://star-gomoku-kids.handsun85.chatgpt.site/>

## 本地运行

这是一个无需构建的静态网站。使用任意静态文件服务器打开 `dist` 目录即可。

## 项目结构

```text
dist/
  index.html   页面结构
  styles.css   视觉样式与响应式布局
  app.js       三种棋类课程、规则和人机练习
```

## 部署

推送到 `main` 分支后，GitHub Actions 会自动把 `dist` 目录发布到 GitHub Pages。

