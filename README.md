# AI Skills 技能库

这是一个用于发布到 ClawHub 的 AI Skills 集合。

## 📦 包含的技能

### 1. Weekly Report Generator (周报生成器)

**目录**: `weekly-report-generator/`

**功能**: 自动从 git 提交记录生成结构化周报

**主要特性**:

- 📊 自动读取指定时间范围的 git 提交记录
- 🏷️ 智能分类工作内容（新功能、Bug 修复、优化、文档等）
- 📝 生成格式化的周报 Markdown 文档
- 🔍 支持多项目、多分支统计
- ⚙️ 可自定义时间范围、格式模板
- 🚀 支持自动发送到飞书

**使用场景**:

- 需要生成周报、总结本周工作
- 需要分析 git 提交记录
- 需要汇报工作进展
- 需要查看 git 提交历史并格式化

**详细文档**: [weekly-report-generator/SKILL.md](./weekly-report-generator/SKILL.md)

---

## 🚀 如何发布到 ClawHub

### 方式一：通过 Git 仓库发布

1. 初始化 Git 仓库（如果还没有）:

   ```bash
   cd /Users/wpp/project/AI/skills
   git init
   ```

2. 添加文件并提交:

   ```bash
   git add .
   git commit -m "feat: 添加周报生成器skill"
   ```

3. 关联远程仓库并推送:

   ```bash
   git remote add origin <your-github-repo-url>
   git branch -M main
   git push -u origin main
   ```

4. 在 ClawHub 上导入你的 GitHub 仓库

### 方式二：直接上传

1. 将整个 `skills` 目录打包为 zip 文件
2. 登录 ClawHub
3. 上传 zip 文件到平台

---

## 📝 技能开发规范

每个技能应该包含：

1. **SKILL.md** - 技能的核心文档，包含：
   - 前置元数据（name, description）
   - 核心功能说明
   - 工作流程
   - 使用示例
   - 注意事项

2. **README.md** (可选) - 技能的简要说明

3. **脚本文件** (可选) - 如果技能需要执行脚本

4. **示例文件** (可选) - 示例输出或模板文件

---

## 🔧 本地测试

在发布前，建议在本地测试技能是否正常工作：

```bash
# 测试周报生成器
# 在支持 skills 的 AI 助手中使用：
# "请使用 weekly-report-generator skill 生成本周周报"
```

---

## 📄 许可证

MIT License

---

## 👤 作者

wangping

---

## 🎯 更新日志

### 2026-04-01

- ✨ 创建技能库项目
- ✨ 添加周报生成器 skill
- 📝 准备发布到 ClawHub

---

## 📮 反馈与建议

如有问题或建议，欢迎通过以下方式联系：

- 提交 Issue
- 发送邮件
- 在 ClawHub 上留言
