# RDS 闲置实例分析报告仪表板

## recovery-dbatest 和 aws-luckyus-pgilkmap-rw 闲置实例分析报告

这是一个基于纯HTML/CSS/JS的交互式仪表板，用于展示 AWS RDS 闲置实例的分析报告。

## 🚀 Vercel 部署

### 方式一：通过 Vercel CLI 部署

```bash
# 安装 Vercel CLI
npm i -g vercel

# 在项目目录下运行
vercel

# 部署到生产环境
vercel --prod
```

### 方式二：通过 GitHub 部署

1. 将此项目推送到 GitHub 仓库
2. 访问 [vercel.com](https://vercel.com)
3. 点击 "New Project"
4. 导入 GitHub 仓库
5. 点击 "Deploy"

### 方式三：通过拖拽部署

1. 访问 [vercel.com/new](https://vercel.com/new)
2. 将整个项目文件夹拖拽到页面上
3. 等待自动部署完成

## 📁 项目结构

```
rds-idle-analysis-dashboard/
├── index.html      # 主仪表板文件
├── vercel.json     # Vercel 配置文件
├── package.json    # 项目元数据
└── README.md       # 本文件
```

## 🎨 功能特性

- ✅ 执行摘要 - 关键指标和实例概览
- ✅ 实例详情 - 详细配置和状态信息
- ✅ 数据库内容 - Schema 分析和数据统计
- ✅ 依赖与风险 - 依赖分析和风险评估矩阵
- ✅ 行动计划 - 操作检查清单和审批流程

## 💰 主要发现

| 实例 | 建议操作 | 月度节省 |
|------|----------|----------|
| recovery-dbatest | 快照后删除 | $48.96 |
| aws-luckyus-pgilkmap-rw | 停止实例 | $254.02 |

**年度节省总计：$3,636**

## 🎯 技术栈

- 纯 HTML5 / CSS3 / JavaScript
- 无外部框架依赖
- 瑞幸咖啡品牌主题色 (Luckin Blue #0066cc)
- 响应式设计

## 🌐 浏览器兼容性

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📝 本地开发

```bash
# 使用 Python
python -m http.server 8080

# 或使用 Node.js
npx serve .
```

然后访问 http://localhost:8080

---

*由 Luckin Coffee US DevOps 团队制作*
