# HollyCRM English Website

一个参考 [sierra.ai](https://sierra.ai) 风格设计的 HollyCRM 英文官方网站。

## 📁 项目结构

```
hollycrm-en/
├── index.html          # 主页面
├── css/
│   └── style.css       # 样式文件
├── js/
│   └── main.js         # JavaScript 交互
├── images/             # 图片资源（待添加）
└── README.md           # 项目说明
```

## 🎨 设计特点

- **现代化设计** - 参考 sierra.ai 的简洁风格
- **响应式布局** - 适配桌面、平板、手机
- **渐变色彩** - 蓝色系渐变主题
- **动画效果** - 平滑过渡和滚动动画
- **交互组件** - Tab 切换、聊天演示动画

## 🚀 快速开始

### 方法 1：直接打开
```bash
# 在浏览器中直接打开
open /Users/duhong/picoding/hollycrm-en/index.html
```

### 方法 2：使用本地服务器
```bash
# 使用 Python
cd /Users/duhong/picoding/hollycrm-en
python3 -m http.server 8080

# 或使用 Node.js
npx serve .
```

然后访问 http://localhost:8080

## 📄 页面内容

### 1. 导航栏 (Navigation)
- Logo
- 产品、解决方案、客户、公司链接
- CTA 按钮

### 2. 英雄区 (Hero Section)
- 主标题和副标题
- CTA 按钮组
- 数据统计展示
- 聊天演示动画

### 3. 产品展示 (Products)
- AI Call Center
- SCRM Platform
- Live Assist
- Analytics Hub

### 4. 行业解决方案 (Solutions)
- 金融服务
- 医疗保健
- 电子商务
- 科技行业

### 5. 客户案例 (Customers)
- 客户评价展示
- 使用效果数据

### 6. CTA 区域
- 行动号召
- 免费试用按钮

### 7. 页脚 (Footer)
- 公司信息
- 产品链接
- 解决方案链接
- 联系方式
- 社交媒体

## 🎯 自定义建议

### 修改品牌色
在 `css/style.css` 中修改 CSS 变量：
```css
:root {
    --color-primary: #2563eb;      /* 主色调 */
    --color-accent: #06b6d4;       /* 强调色 */
}
```

### 添加 Logo
替换 `.logo-text` 为图片：
```html
<a href="/" class="logo">
    <img src="images/logo.png" alt="HollyCRM">
</a>
```

### 修改内容
编辑 `index.html` 中的文本内容，替换为实际的：
- 公司名称
- 产品描述
- 客户案例
- 联系方式

## 📱 响应式断点

| 断点 | 宽度 | 布局变化 |
|------|------|----------|
| Desktop | > 1024px | 完整布局 |
| Tablet | 768px - 1024px | 2 列网格 |
| Mobile | < 768px | 单列布局 |

## 🔧 技术栈

- **HTML5** - 语义化标签
- **CSS3** - 自定义属性、Grid、Flexbox
- **JavaScript (ES6+)** - 原生 JS，无依赖
- **动画** - CSS Animations + Intersection Observer

## 📝 待完成

- [ ] 添加实际 Logo 图片
- [ ] 添加产品截图/演示图片
- [ ] 添加客户 Logo
- [ ] 联系表单功能
- [ ] 多语言支持
- [ ] SEO 优化
- [ ] 性能优化（图片懒加载等）

## 📄 许可证

MIT License

---

**创建时间**: 2026-04-06  
**参考设计**: [sierra.ai](https://sierra.ai)  
**目标网站**: [hollycrm.com](https://www.hollycrm.com)
