# 网站部署指南

## 🚨 快链部署问题解决

### 常见问题及解决方案

#### 1. 文件路径问题
**问题**：中文字符路径可能导致部署失败
**解决**：确保上传时路径不包含中文，或使用英文目录名

#### 2. Chart.js CDN问题
**问题**：某些平台可能无法访问国外CDN
**解决**：将Chart.js下载到本地

#### 3. 平台兼容性
**问题**：不同平台对HTML/CSS/JS的支持不同
**解决**：使用更兼容的代码写法

### 快速解决方案

#### 方案1：使用GitHub Pages（推荐）
1. 将代码上传到GitHub仓库
2. 在Settings中开启GitHub Pages
3. 选择main分支作为源

#### 方案2：使用Netlify
1. 访问netlify.com
2. 拖拽文件夹到部署区域
3. 等待自动部署完成

#### 方案3：修复快链部署
1. 检查文件是否完整上传
2. 确认index.html在根目录
3. 等待平台处理完成（可能需要几分钟）

### 兼容性修复代码

#### 本地Chart.js
如果CDN访问有问题，可以下载Chart.js到本地：
```bash
# 下载Chart.js
curl -o chart.js https://cdn.jsdelivr.net/npm/chart.js
```

然后修改HTML中的引用：
```html
<script src="chart.js"></script>
```

#### 检查文件完整性
确保以下文件都已上传：
- index.html
- test.html  
- result.html
- css/style.css
- js/main.js
- questions_data.json

### 部署验证
部署完成后，检查：
1. 首页是否正常显示
2. 能否正常跳转到测试页面
3. 题目是否正常显示
4. 结果页面是否工作

如果仍有问题，请提供具体的错误信息以便进一步诊断。