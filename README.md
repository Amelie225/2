# 我的个人空间

这是一个基于React的个人空间网站，具有照片轮播、对话界面和社交媒体链接等功能。

## 功能特点

- **响应式设计**：适配不同屏幕尺寸
- **照片轮播**：自动轮播照片，支持手动切换
- **对话界面**：与AI助手交流的聊天界面
- **社交媒体链接**：展示社交媒体账号

## 技术栈

- React
- styled-components
- react-icons

## 项目结构

```
my-personal-space/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── assets/
│   │   └── images/
│   ├── components/
│   │   ├── Navbar.js
│   │   ├── PhotoCarousel.js
│   │   ├── ChatInterface.js
│   │   └── SocialLinks.js
│   ├── App.js
│   ├── index.js
│   └── index.css
└── package.json
```

## 安装与运行

1. 克隆项目

```bash
git clone <仓库地址>
cd my-personal-space
```

2. 安装依赖

```bash
npm install
```

3. 启动开发服务器

```bash
npm start
```

应用将在 http://localhost:3000 运行。

## 自定义

### 添加照片

1. 在 `src/assets/images` 目录中添加图片
2. 修改 `src/components/PhotoCarousel.js` 文件中的 `sampleImages` 数组

### 修改社交媒体链接

修改 `src/components/SocialLinks.js` 文件中的 `socialPlatforms` 数组。

## 构建生产版本

```bash
npm run build
```

构建文件将生成在 `build` 目录中。 