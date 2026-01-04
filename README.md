# RPI情侣占有欲指数评测网站 💕

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/your-username/couple-possessiveness-assessment)](https://github.com/your-username/couple-possessiveness-assessment/issues)
[![GitHub stars](https://img.shields.io/github/stars/your-username/couple-possessiveness-assessment)](https://github.com/your-username/couple-possessiveness-assessment/stargazers)

一个基于科学心理学的情侣占有欲指数测评网站，通过专业的问卷评估帮助用户了解自己在亲密关系中的占有欲相关特质。

## ✨ 功能特点

- 🎯 **智能随机测评**：从50道专业题目中随机选择20道，确保评估的全面性
- 📊 **四维度科学分析**：
  - 控制欲望 (Control Desire)
  - 嫉妒强度 (Jealousy Intensity) 
  - 情感依赖 (Emotional Dependence)
  - 关系不安全感 (Relationship Insecurity)
- 📈 **雷达图可视化**：直观展示各维度得分
- 💡 **个性化改进建议**：基于测评结果提供专业建议
- 💾 **进度保存**：支持断点续测，使用localStorage保存进度
- 📱 **响应式设计**：完美适配PC和移动设备
- 🎨 **优雅界面**：现代化的UI设计，操作简单直观

## 🚀 在线体验

网站现已部署在GitHub Pages，可直接访问体验：
**[立即开始测评](https://your-username.github.io/couple-possessiveness-assessment/)**

## 🛠️ 技术栈

- **前端框架**：原生HTML5 + CSS3 + JavaScript (ES6+)
- **图表库**：[Chart.js](https://www.chartjs.org/) - 数据可视化
- **数据存储**：浏览器localStorage - 本地数据持久化
- **部署平台**：GitHub Pages / Netlify / Vercel

## 📁 项目结构

```
couple-possessiveness-assessment/
├── index.html          # 首页
├── test.html          # 测评页面
├── result.html        # 结果展示页
├── questions_data.json # 题库数据
├── js/
│   └── main.js        # 核心业务逻辑
├── css/
│   └── style.css      # 样式文件
├── public/
│   └── _redirects     # Netlify路由配置
└── README.md          # 项目说明
```

## 🚀 快速开始

### 本地运行

1. **克隆项目**
   ```bash
   git clone https://github.com/your-username/couple-possessiveness-assessment.git
   cd couple-possessiveness-assessment
   ```

2. **启动本地服务器**
   ```bash
   # 使用Python
   python -m http.server 8080
   
   # 或使用Node.js
   npx serve .
   ```

3. **访问应用**
   打开浏览器访问：`http://localhost:8080`

### 部署到GitHub Pages

1. Fork此项目到你的GitHub账户
2. 进入项目Settings > Pages
3. 选择部署源为"GitHub Actions"
4. 等待自动部署完成

## 📖 使用说明

1. **开始测评**：访问首页，点击"开始测评"按钮
2. **答题过程**：系统会随机选择20道题目，每次5道来自不同维度
3. **查看结果**：完成答题后查看雷达图和详细分析
4. **获取建议**：根据测评结果获得个性化的改进建议

## 🎯 测评维度说明

| 维度 | 说明 | 分数范围 |
|------|------|----------|
| 控制欲望 | 对伴侣行为的控制需求程度 | 0-100 |
| 嫉妒强度 | 对伴侣与他人互动的敏感度 | 0-100 |
| 情感依赖 | 对伴侣情感依赖的程度 | 0-100 |
| 关系不安全感 | 对关系稳定性的担忧程度 | 0-100 |

## 🔄 版本历史

- **v2.0** - 优化测评体验，增加个性化建议
- **v1.5** - 改进UI设计，提升响应式体验  
- **v1.0** - 基础测评功能实现

## 🤝 贡献指南

欢迎提交Issue和Pull Request！

1. Fork本项目
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 📞 联系方式

- 项目链接：[https://github.com/your-username/couple-possessiveness-assessment](https://github.com/your-username/couple-possessiveness-assessment)
- 问题反馈：[https://github.com/your-username/couple-possessiveness-assessment/issues](https://github.com/your-username/couple-possessiveness-assessment/issues)

---

**免责声明**：此测评工具仅供参考，不能替代专业的心理咨询或诊断。如有需要，请寻求专业心理帮助。