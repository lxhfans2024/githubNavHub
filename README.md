# GitHub Navigation Hub

```ascii
🌐 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 🚀
│                                                │
│             GitHub Navigation Hub              │
│         Developer's Essential Links            │
│                                                │
🔗 ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 🌟
```

一个优雅的开发者导航网站，采用 GitHub 深色主题风格设计。

## 特性

- 🎨 GitHub 深色主题风格
  - 优雅的深色配色方案
  - GitHub 风格的 UI 元素
  - 旋转的 GitHub Logo
  - 平滑的动画效果

- 📱 响应式设计
  - 完美适配桌面端
  - 自适应平板设备
  - 优化移动端显示
  - 流畅的交互体验

- 🔍 分类导航
  - AI搜索工具
  - 实用开发工具
  - 社交媒体平台
  - 科技资讯媒体
  - 云存储服务
  - 电子邮箱服务

- ⚡ 高性能
  - 纯静态页面
  - 快速加载
  - 无需后端
  - 零依赖部署

## 部署指南

### 方式一：GitHub Pages

1. Fork 本仓库
2. 进入仓库设置 Settings
3. 找到 Pages 设置项
4. Source 选择 `main` 分支
5. 点击 Save 保存
6. 等待几分钟后访问 `https://<你的用户名>.github.io/githubNavHub`

### 方式二：Cloudflare Pages

1. Fork 本仓库
2. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
3. 进入 Pages 项目
4. 点击 "Create a project"
5. 选择 "Connect to Git"
6. 选择你 fork 的仓库
7. 部署设置保持默认
8. 点击 "Save and Deploy"
9. 等待部署完成即可通过分配的域名访问

## 自定义配置

### 修改网站标题

```html
<div class="header">
  <svg class="github-logo" height="32" viewBox="0 0 16 16" width="32">...</svg>
  <h1>GitHub Navigation Hub</h1>
  <span class="header-subtitle">Developer's Essential Links Collection</span>
</div>
```

### 修改主题颜色

```css
:root {
  --bg-color: #0d1117;    /* 背景色 */
  --card-bg: #161b22;     /* 卡片背景 */
  --border-color: #30363d;/* 边框颜色 */
  --text-color: #c9d1d9;  /* 文字颜色 */
  --link-color: #58a6ff;  /* 链接颜色 */
  --hover-bg: #21262d;    /* 悬停背景 */
}
```

### 添加新的链接

```html
<section class="link-grid">
  <a href="你的链接" class="nav-link" target="_blank">
    <span class="link-icon"><i class="fas fa-icon"></i></span>
    网站名称
  </a>
</section>
```

## 特色功能

- 🌙 深色主题
- 🎯 平滑滚动
- 💫 动画效果
- 📱 响应式布局
- 🔍 分类导航
- 🎨 优雅界面

## 技术栈

- HTML5
- CSS3 (Flexbox & Grid)
- Vanilla JavaScript
- Font Awesome 5
- GitHub 深色主题

## 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 开源协议

本项目采用 MIT 协议 - 查看 [LICENSE](LICENSE) 文件了解详情

## 致谢

- [Font Awesome](https://fontawesome.com/) - 图标库
- [GitHub](https://github.com/) - 设计灵感

## 联系方式

项目链接：[https://github.com/bbylw/githubNavHub](https://github.com/bbylw/githubNavHub)
