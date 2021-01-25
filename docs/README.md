# vuepress-template

> vuepress 模板

## 目录结构

```auto
.
├── docs
│   ├── .vuepress (可选的，存放全局配置、组件、静态资源等)
│   │   ├── components (可选的，全局组件)
│   │   ├── theme (可选的，主题)
│   │   │   └── Layout.vue
│   │   ├── public (可选的，静态资源)
│   │   ├── styles (可选的，样式)
│   │   │   ├── index.styl（全局样式，会覆盖默认样式）
│   │   │   └── palette.styl（用于重写颜色常量）
│   │   ├── templates (可选的, 谨慎配置，模板文件)
│   │   │   ├── dev.html（开发环境模板）
│   │   │   └── ssr.html（SSR模板）
│   │   ├── config.js (可选的，配置文件的入口文件)
│   │   └── enhanceApp.js (可选的，客户端应用的增强)
│   │
│   ├── README.md
│   ├── guide
│   │   └── README.md
│   └── config.md
│
└── package.json


```
