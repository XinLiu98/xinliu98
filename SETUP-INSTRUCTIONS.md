# GitHub Profile README 设置完成指南

## ✅ 已完成
- ✅ 创建了 `XinLiu98` 目录
- ✅ 创建了 `README.md` 文件

## 📋 下一步操作

### 1. 在 GitHub 上创建仓库

访问：https://github.com/new

**重要设置：**
- **仓库名**：`XinLiu98`（必须与你的 GitHub 用户名完全相同）
- **可见性**：选择 **Public**（公开）
- ⚠️ **不要**勾选 "Add a README file"
- ⚠️ **不要**添加 .gitignore
- ⚠️ **不要**添加 license

点击 "Create repository" 创建仓库。

### 2. 初始化并推送代码

打开终端，执行以下命令：

```bash
# 进入目录
cd ~/XinLiu98

# 初始化 Git 仓库
git init

# 添加 README.md
git add README.md

# 创建提交
git commit -m "Initial commit: Add GitHub Profile README"

# 添加远程仓库（使用 SSH）
git remote add origin git@github.com:XinLiu98/XinLiu98.git

# 或者使用 HTTPS（如果 SSH 未配置）
# git remote add origin https://github.com/XinLiu98/XinLiu98.git

# 重命名分支为 main
git branch -M main

# 推送到 GitHub
git push -u origin main
```

### 3. 验证

推送成功后，访问你的 GitHub 个人资料页面：
https://github.com/XinLiu98

你应该能看到 README 内容显示在你的个人资料页面顶部！

## 🎨 自定义 README

你可以随时编辑 `README.md` 文件来自定义你的 Profile：

```bash
cd ~/XinLiu98
# 编辑 README.md
# 然后提交并推送
git add README.md
git commit -m "Update profile README"
git push
```

## 💡 提示

- README 支持 Markdown 和 HTML
- 可以使用各种徽章和图标
- GitHub Stats 会自动更新
- 修改后推送到 GitHub，几分钟内就会显示更新

## ❓ 常见问题

**Q: README 不显示？**
A: 确认仓库名与用户名完全相同，仓库是 Public，README.md 在根目录。

**Q: 推送失败？**
A: 检查 SSH 密钥是否已添加到 GitHub，或使用 HTTPS 方式。

**Q: 如何更新 README？**
A: 编辑 README.md，然后 `git add`、`git commit`、`git push`。

