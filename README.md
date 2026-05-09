# ✦ 星澜 Star

> AI智能播客应用 - 移动端优先的深色科技风UI播客平台

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Mobile-ff69b4)

## 🌟 特性

- **AI智能生成** - 输入主题，选择风格，AI自动生成完整播客内容
- **语义搜索** - 支持同义词扩展和模糊匹配，精准找到想要的内容
- **个性化推荐** - 基于用户兴趣的智能推荐算法
- **实时热点** - 追踪最新最热的播客专辑
- **精致播放器** - 迷你播放器 + 全屏播放器，支持实时文稿滚动

## 🎨 设计

- 深色科技风UI，星空蓝紫渐变基调
- 移动端优先设计，流畅的交互动画
- 响应式布局，适配各种屏幕尺寸

## 🛠️ 技术栈

- 原生 HTML5 + CSS3 + JavaScript (ES6+)
- CSS变量管理主题系统
- localStorage 数据持久化
- Lucide Icons 图标库
- Google Fonts (Noto Sans SC)

## 📦 使用

### 直接打开
```bash
# 在浏览器中直接打开 index.html
open index.html
```

### 本地服务器
```bash
# 使用 Python
python -m http.server 8080

# 使用 Node.js
npx serve .

# 使用 PHP
php -S localhost:8080
```

然后访问 `http://localhost:8080`

## 📱 功能模块

### 页面
- [x] 启动页 - 品牌Logo + 加载动画
- [x] 登录/注册 - 手机号/邮箱、第三方登录、验证码
- [x] 兴趣选择 - 首次登录引导，标签网格选择
- [x] 首页 - 热点轮播 + 个性化推荐 + 最新单集
- [x] 发现 - AI语义搜索 + 分类浏览
- [x] 动态 - 专辑更新时间线
- [x] 我的 - 用户信息 + 快捷入口
- [x] AI生成 - 主题输入 + 风格选择 + 高级设置
- [x] 播放器 - 迷你播放器 + 全屏播放器 + 文稿滚动
- [x] 设置 - 主题、通知、缓存管理等

### 功能
- [x] 用户认证系统
- [x] AI生成播客
- [x] AI语义搜索
- [x] 收藏和历史记录
- [x] 数据持久化存储

## 📄 目录结构

```
radio_star/
├── index.html          # 完整应用（单文件）
├── README.md           # 项目文档
├── LICENSE             # MIT许可证
└── .gitignore          # Git忽略配置
```

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

本项目基于 MIT 许可证开源。

## 👤 作者

**星澜 Star**

## 🙏 致谢

- [Lucide Icons](https://lucide.dev/) - 精美图标库
- [Google Fonts](https://fonts.google.com/) - Noto Sans SC 字体
