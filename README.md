# AI Daily Summary

每日 AI（大模型、Agent、开源项目）热点自动总结。

- 由 [ai-daily-summary](https://github.com/lurea-git/grok-project/tree/main/.grok/skills/ai-daily-summary) Skill 自动生成
- 内容来源：X (Twitter) + Reddit
- 严格质量过滤 + 分类（官方更新、模型研究、Agent、开源、社区讨论、实用 Skill）
- 每类最多 TOP 10 热点
- 美观响应式 HTML，支持日期切换

## 访问

GitHub Pages: https://lurea-git.github.io/ai-daily/

## 使用

在 grok-project 项目中使用：

```bash
grok -p "今天AI总结" --yolo
```

报告会输出到本目录，并可自动推送到此仓库。

## 结构

- `index.html` - 主页 + 日期选择器 + 各分类概览
- `ai-daily-YYYY-MM-DD.html` - 当日完整报告

## 部署

本仓库已配置 GitHub Pages（main 分支根目录）。
