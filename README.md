# 板仓 PedalBoard — 交互式 PRD

> 效果器垂直社区 | 交互式产品需求文档 | 2026

## 这是什么？

**板仓**是一个面向效果器爱好者的垂直社区产品原型。本项目采用"交互式 PRD"的形式——在浏览器中可点击、可交互的高保真原型，比静态文档更直观，比开发 MVP 成本更低。

## 项目内容

| 文件 | 说明 |
|------|------|
| [index.html](index.html) | 项目入口展示页 |
| [prototypes/home-glassmorphism.html](prototypes/home-glassmorphism.html) | 首页 Feed — 帖子流、搜索、Tab 切换 |
| [prototypes/discover.html](prototypes/discover.html) | 发现页 — 分类卡片、排行榜、效果器详情弹窗 |
| [prototypes/publish-post-flow.html](prototypes/publish-post-flow.html) | 发布流程 — 表单验证、状态机、错误处理 |
| [prototypes/messages.html](prototypes/messages.html) | 消息页 — 互动通知、私信会话 |
| [prototypes/profile.html](prototypes/profile.html) | 个人主页 — 用户资料、Tab 切换、帖子管理 |
| [PRD.md](PRD.md) | 产品需求文档（15 章完整规划） |

**每个原型页面左下角有"DN"按钮，点击可查看 30+ 交互标注和开发说明。**

## 在线预览

> 部署后在此粘贴链接

## 技术说明

- 纯静态 HTML/CSS/JS，零依赖
- Glassmorphism 毛玻璃设计系统
- CSS 自定义属性（设计令牌）驱动的主题
- 响应式手机框架（390x844px）
- 点击 "DN" 按钮显示/隐藏交互标注

## 项目定位

- **目标用户**：效果器爱好者、商家、内容创作者（KOL）
- **核心路径**：发现效果器 → 查看排行/详情 → 评估决策 → 交流讨论
- **当前阶段**：交互式 PRD（用于与开发者沟通产品需求）
- **下一步**：效果器数据库接入 → 真实用户系统 → 可部署 MVP
