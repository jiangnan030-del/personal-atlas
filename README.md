# Personal Atlas

[![Deploy static site to GitHub Pages](https://github.com/jiangnan030-del/personal-atlas/actions/workflows/pages.yml/badge.svg)](https://github.com/jiangnan030-del/personal-atlas/actions/workflows/pages.yml)

Jiangnan 的个人网站 MVP：产品、AI 与体验设计。

**线上网站：** https://jiangnan030-del.github.io/personal-atlas/

## 特性

- Fast / Explore 双层体验
- 响应式能力图谱
- 项目 Story / Data / Method 证据模式
- 本地 Personal AI 交互演示
- Now 页面与联系路径
- 键盘导航、reduced-motion、语义化 HTML
- 无框架、零构建依赖，可直接部署

## 本地运行

```bash
python3 -m http.server 8080
```

访问 `http://localhost:8080`。

## 部署

项目通过 GitHub Actions 自动部署至 GitHub Pages。推送到 `main` 分支后会自动发布。

## 下一步

1. 替换真实项目素材与案例证据。
2. 接入基于公开资料的 RAG Personal AI，并为回答显示来源。
3. 为项目补充 Open Graph 图片与 JSON-LD。
4. 通过真实设备完成 WCAG 2.2 AA 与性能验收。

## License

MIT
