# AAAguosai

比赛协作项目仓库。

## 项目简介

本项目用于比赛协作开发，围绕比赛要求构建完整解决方案。详细说明待补充。

## 目录结构

```
AAAguosai/
├── .github/          # GitHub 配置（Actions 工作流等）
├── README.md         # 项目说明
└── LICENSE           # 开源协议
```

## 快速开始

```bash
# 克隆仓库（需要协作者权限）
git clone https://github.com/trixster2/AAAguosai.git
cd AAAguosai

# 创建自己的功能分支
git checkout -b feature/你的功能名

# 开发完成后提交并推送
git add .
git commit -m "feat: 添加 xxx 功能"
git push -u origin feature/你的功能名
```

## 协作流程（Issue → 分支 → PR → 审查 → 合并）

1. **提 Issue**：新任务先在 Issues 里创建，说明背景与验收标准
2. **建分支**：从 `main` 拉取新分支，命名规范：
   - `feature/xxx` — 新功能
   - `fix/xxx` — 缺陷修复
   - `docs/xxx` — 文档修改
   - `ci/xxx` — CI 相关
3. **提交规范**：`type: 描述`，如 `feat:`、`fix:`、`docs:`、`ci:`；可用 `Closes #编号` 关联 Issue
4. **提 PR**：推送分支后在 GitHub 上创建 Pull Request，@ 相关成员审查
5. **代码审查**：审查者评论、提建议，通过后合并
6. **合并策略**：普通提交（`--merge`）、压缩合并（`--squash`）、变基合并（`--rebase`）按需选择

## 自动化（CI）

仓库已配置 GitHub Actions，每次 push 和 PR 都会自动运行检查，可在 **Actions** 标签页查看结果。

## 版本发布

使用 Git Tag + Release 管理版本，如 `v0.1.0`。

## 许可

[MIT](LICENSE)