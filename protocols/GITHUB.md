# Agent 公司 - GitHub协作指南

## 概览
GitHub代码管理已安装到 `.skills/github-manager/`

## 能力范围
- ✅ 代码仓库管理
- ✅ Issue 创建与追踪
- ✅ PR 创建与审查
- ✅ Release 发布
- ✅ Actions 工作流调度
- ✅ 代码提交与推送

## 使用前提
- 需要 GitHub Personal Access Token
- 需要配置在环境变量或凭据中

## 触发方式
- `github` / `git` - 通用 Git 操作
- `创建PR` - 创建 Pull Request
- `提交代码` - git commit & push
- `查看issue` - 查看 GitHub Issues

## Agent协作流程
```
用户需求涉及GitHub
       ↓
   零判断复杂度
       ↓
   码灵/构架 执行具体操作
       ↓
   结果汇报用户
```

## 典型场景
1. **创建项目代码仓库** → 构架设计 → 码灵实现 → 推送到GitHub
2. **代码审查** → 码灵审查 → 凌风协调讨论
3. **多人协作** → 凌风统筹 → 各Agent分工

## 注意事项
- 敏感操作（删除仓库等）需用户确认
- 建议先在本地测试再推送
- 保持 commit 信息清晰
