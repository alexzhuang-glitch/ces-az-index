# 🚀 部署指南 - 5分钟让网站上线

> 本指南将帮助你将 CES-AZ-INDEX 网站部署到 GitHub Pages，获得永久访问地址

---

## 📋 准备工作

你需要：
- [x] GitHub 账号: `alexzhuang-glitch` ✅
- [x] 网站文件 ✅ (已准备好)
- [ ] 5分钟时间

---

## 🎯 部署步骤（图文版）

### 步骤 1: 登录 GitHub
1. 打开 https://github.com
2. 用 `alexzhuang-glitch` 账号登录

---

### 步骤 2: 创建新仓库

1. 点击右上角 **"+"** 按钮
2. 选择 **"New repository"**

```
Repository name: ces-az-index
Description: CES Innovation Awards Database 2024-2026
Visibility: Public ✅ (必须选公开)
```

3. 点击 **"Create repository"**

---

### 步骤 3: 上传文件

**方法一：网页上传（推荐，最简单）**

1. 在新仓库页面，找到 **"uploading an existing file"** 链接，点击它

2. 将以下文件拖入上传区域：
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `DEPLOY.md`
   - `data/products.json`
   - `data/stats.json`
   - `data/tracks.json`
   - `data/countries.json`
   - `data/categories.json`

3. 在 "Commit changes" 区域，填写：
   ```
   Commit message: Initial commit - CES Innovation Awards Database
   ```

4. 点击 **"Commit changes"**

---

### 步骤 4: 启用 GitHub Pages

1. 在仓库页面，点击顶部的 **"Settings"** 标签

2. 左侧菜单找到并点击 **"Pages"**

3. 在 "Build and deployment" 部分：
   - **Source**: 选择 "Deploy from a branch"
   - **Branch**: 选择 "main"，文件夹选择 "/ (root)"

4. 点击 **"Save"**

---

### 步骤 5: 等待部署

1. 等待 1-2 分钟
2. 刷新页面
3. 你会看到绿色提示：
   ```
   Your site is live at https://alexzhuang-glitch.github.io/ces-az-index
   ```

---

### 步骤 6: 访问你的网站

🎉 **网站地址**: https://alexzhuang-glitch.github.io/ces-az-index

---

## ✅ 验证部署成功

打开网站后，检查以下内容：

- [ ] 页面标题显示 "CES-AZ-INDEX"
- [ ] 右上角显示 "1,432 Total Products"
- [ ] 能看到 "Hot Tracks Analysis" 卡片
- [ ] 点击 "Database" 标签能看到产品列表
- [ ] 图表正常显示

---

## 🐛 常见问题

### Q1: 网站显示 404
**原因**: GitHub Pages 需要时间部署
**解决**: 等待 2-3 分钟后刷新

### Q2: 页面空白，没有数据
**原因**: data 文件夹没有上传
**解决**: 确保上传了 data 文件夹中的所有 .json 文件

### Q3: 图表不显示
**原因**: 网络问题导致 Chart.js 加载失败
**解决**: 刷新页面或检查网络连接

### Q4: 想更新网站内容怎么办？
**解决**:
1. 修改本地文件
2. 重新上传到 GitHub
3. 自动重新部署（约1分钟）

---

## 🌐 绑定自定义域名（可选）

如果你想要 `www.ces-az-index.com`：

### 1. 购买域名
- 阿里云: https://wanwang.aliyun.com
- GoDaddy: https://www.godaddy.com
- 费用: 约 ¥50-100/年

### 2. 配置 DNS
在域名管理后台添加 CNAME 记录：
```
主机记录: www
记录值: alexzhuang-glitch.github.io
```

### 3. 在 GitHub 配置
1. 进入仓库 Settings → Pages
2. 在 "Custom domain" 输入: `www.ces-az-index.com`
3. 点击 "Save"
4. 勾选 "Enforce HTTPS"

### 4. 等待生效
- DNS 生效需要 10-30 分钟
- 访问 `www.ces-az-index.com` 即可

---

## 📞 需要帮助？

如果遇到问题：

1. 检查浏览器控制台 (F12) 查看错误信息
2. 确认所有文件已正确上传
3. 参考 GitHub Pages 官方文档: https://docs.github.com/en/pages

---

**🎉 部署完成后，你就拥有了一个真正的公开网站！**
