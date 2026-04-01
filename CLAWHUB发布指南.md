# ClawHub 发布指南

本指南将帮助你将周报生成器 Skill 发布到 ClawHub 平台。

## 📋 发布前检查清单

在发布之前，请确保：

- ✅ 所有脚本文件已包含在项目中
- ✅ 文档完整且清晰（SKILL.md, README.md, 安装指南等）
- ✅ 已测试 Skill 功能正常
- ✅ 已移除敏感信息（如 APP_SECRET, RECEIVE_ID 等）
- ✅ Git 仓库已初始化并提交

---

## 🚀 发布方式

### 方式一：通过 GitHub 发布（推荐）

这是最推荐的方式，便于版本管理和协作。

#### 步骤 1：创建 GitHub 仓库

1. 登录 [GitHub](https://github.com)
2. 点击右上角 "+" → "New repository"
3. 填写仓库信息：
   - **Repository name**: `ai-skills` 或 `weekly-report-skill`
   - **Description**: `AI周报生成器Skill - 自动从git提交生成周报并发送到飞书`
   - **Visibility**: Public（公开）或 Private（私有）
4. 不要勾选 "Initialize this repository with a README"
5. 点击 "Create repository"

#### 步骤 2：推送代码到 GitHub

```bash
cd /Users/wpp/project/AI/skills

# 如果还没有初始化 git（已初始化可跳过）
git init
git add .
git commit -m "feat: 添加周报生成器skill"

# 关联远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/your-username/ai-skills.git

# 推送代码
git branch -M main
git push -u origin main
```

#### 步骤 3：在 ClawHub 导入
