# 社保管理系统 - 首页看板

## 项目简介

这是一个社保管理系统的内部仪表板项目，提供全面的业务监控和数据分析功能。通过可视化的方式展示关键业务指标、流程进度和异常监控，帮助管理者快速了解系统运行状态并做出决策。

## 在线访问

🌐 **在线演示**: [点击这里查看仪表板](https://cedricz73.github.io/social-security-dashboard/dashboard.html)

## 功能特性

### 📅 社保日历模块
- 展示各主体的关键时间节点信息
- 显示各主体关账日、调基时间、缴费时间节点
- 支持点击跳转至对应详情页面

### 📊 关键指标卡模块
- 人员总数统计
- 账户数据监控
- 规则数据管理
- 派单与订单管理
- 异常监控和预警

### 📈 数据可视化
- 实时业务数据监控
- 多维度数据筛选和下钻分析
- 异常情况及时预警
- 交互式图表展示

## 文件结构

```
├── dashboard.html                      # 主仪表板页面
├── dashboard-requirements-update.md    # 需求更新文档
├── product-requirements-document.md    # 产品需求文档
├── system-modules-overview.md         # 系统模块概述
└── README.md                          # 项目说明文档
```

## 本地运行

1. 克隆仓库到本地
2. 直接在浏览器中打开 `dashboard.html` 文件
3. 或者使用本地服务器：
   ```bash
   python3 -m http.server 8000
   ```
   然后访问 `http://localhost:8000/dashboard.html`

## 技术栈

- **前端**: HTML5, CSS3, JavaScript
- **图表库**: ECharts 5.4.3
- **样式**: 响应式设计，支持移动端
- **部署**: GitHub Pages

## 更新日志

- **2024-10-30**: 初始版本发布，包含完整的仪表板功能

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目。

## 许可证

本项目仅供内部使用。
