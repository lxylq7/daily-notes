# Daily Commit 🗓️

每天自动从 `phrases.txt` 随机选一句话，提交到 `daily.md`。

## 使用方法

1. **编辑句子**：修改 `phrases.txt`，每行一句话，可以带 emoji
2. **修改时间**：编辑 `.github/workflows/daily-commit.yml` 中的 `cron` 表达式
3. **推送到 GitHub**：创建仓库后推送即可自动运行

## 工作流说明

- 每天 08:00（北京时间）自动运行
- 随机从 `phrases.txt` 选一句话
- 追加到 `daily.md` 并自动 commit + push
- 也支持在 GitHub Actions 页面手动触发
