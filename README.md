# 🌟 燧之门户 | Personal Portal

> ✨ 一个融合东方美学与现代设计的个人门户网站

基于 **Astro** + **Tailwind CSS** 构建的个人展示网站，集成太极五行熔合系统、多主题切换、响应式三栏布局等特色功能。

## 📸 预览

🔗 **在线访问**: [sunyzhi55.github.io](https://sunyzhi55.github.io)

## ✨ 特色功能

- 🎨 **多彩主题系统** - 支持预设配色 + 自定义色相调节，明暗模式切换
- ☯️ **太极五行熔合** - 独创的五行元素交互系统，50+ 种熔合结果
- 🖼️ **动态背景** - 纯色/渐变/轮播图三种背景模式
- 📱 **响应式设计** - 完美适配桌面端与移动端
- 🎵 **媒体收藏** - 音乐播放器 + 图片画廊
- 📜 **时间轴** - 个人经历展示
- 🔗 **站点导航** - 多站点部署信息聚合

## 🏗️ 项目结构

```text
/
├── public/                 # 静态资源
│   ├── avatar/            # 头像图片
│   ├── gallery/           # 图库图片
│   ├── music/             # 音乐文件
│   └── WuxingFusion.json  # 五行熔合配置
├── src/
│   ├── components/        # 组件
│   │   ├── Header.astro          # 导航栏 & 主题切换
│   │   ├── Hero.astro            # 欢迎区域
│   │   ├── ProfileCard.astro     # 个人信息卡片
│   │   ├── RightSidebar.astro    # 右侧边栏
│   │   ├── FunTabs.astro         # 趣味标签页
│   │   ├── WuxingTaiji.astro     # 太极五行系统
│   │   ├── MediaCollection.astro # 媒体收藏
│   │   ├── Timeline.astro        # 时间轴
│   │   └── ...
│   ├── layouts/           # 布局模板
│   │   └── Layout.astro
│   ├── pages/             # 页面
│   │   └── index.astro
│   └── styles/            # 样式
│       └── global.css
├── biome.json             # Biome 配置
├── astro.config.mjs       # Astro 配置
└── package.json
```

## 🚀 快速开始

### 环境要求

- Node.js >= 18.0.0
- npm >= 9.0.0

### 安装依赖

```bash
npm install
```

### 开发命令

| 命令 | 说明 |
|:-----|:-----|
| `npm run dev` | 🔧 启动开发服务器 (`localhost:4321`) |
| `npm run build` | 📦 构建生产版本到 `./dist/` |
| `npm run preview` | 👀 本地预览构建产物 |
| `npm run format` | 🎨 格式化代码 |
| `npm run lint` | 🔍 代码检查 |
| `npm run check:fix` | ✅ 自动修复格式 & lint 问题 |

## 🎨 主题系统

### 配色方案

| 主题 | 色相 | 说明 |
|:-----|:-----|:-----|
| 🟡 琥珀金 | 35° | 默认主题，温暖典雅 |
| 🔵 靛青蓝 | 210° | 冷静理性 |
| 🟢 翠玉绿 | 145° | 自然清新 |
| 🔴 朱砂红 | 0° | 热情奔放 |
| 🟣 紫晶石 | 270° | 神秘高贵 |

此外支持 **自定义色相滑块**（0°-360°）和 **全局主题**（赛博朋克、日落黄昏等）。

## ☯️ 五行熔合系统

选择 **金、木、水、火、土、日、月** 七种元素进行组合熔合，产生独特的哲学结果：

- 单元素：如 `金` → 锐气
- 双元素：如 `水 + 火` → 既济
- 多元素：如 `金 + 木 + 水 + 火 + 土` → 太和
- 特殊组合：如 `日 + 月` → 明

共 **50+ 种** 熔合结果，每个结果包含名称、符号、诗句和哲学释义。

## 🛠️ 技术栈

- ⚡ **[Astro](https://astro.build)** - 静态站点生成器
- 🎨 **[Tailwind CSS v4](https://tailwindcss.com)** - 原子化 CSS 框架
- 🔧 **[Biome](https://biomejs.dev)** - 代码格式化 & Lint
- 📝 **TypeScript** - 类型安全

## 📄 许可证

MIT License © 2026 [sunyzhi55](https://github.com/sunyzhi55)

---

<p align="center">
  Made with ❤️ and ☯️
</p>
