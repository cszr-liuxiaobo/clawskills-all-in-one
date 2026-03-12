---
name: academic-paper-reader
description: |
  学术论文阅读与分析助手。用于搜索、获取、阅读和总结学术论文。
  
  触发场景：
  (1) 用户要求查找某个主题的论文
  (2) 用户要求阅读、总结、分析学术论文
  (3) 用户提到论文、paper、academic、journal、arXiv、PubMed等
  (4) 用户要求追踪最新学术动态或某个领域的前沿研究
  (5) 用户发送论文PDF或论文链接要求分析
---

# 学术论文阅读助手 - Academic Paper Reader

> 🎯 **一句话说明**：帮助搜索、阅读、总结学术论文的AI助手

> 🌐 **Language / 语言**: [中文](./SKILL.md) | [English](./SKILL_EN.md)

---

## 🚀 一键安装（推荐）

直接对我说：
```
帮我安装 academic-paper-reader skill（https://github.com/cszr-liuxiaobo/clawskills-all-in-one/tree/main/skills/academic-paper-reader）
```

我会自动：
1. 读取SKILL.md了解这个skill
2. 复制到OpenClaw的skills目录
3. 在配置文件中启用它

---

## 📥 手动安装

在 `openclaw.json` 的 `skills.entries` 中添加：

```json
"academic-paper-reader": {
  "enabled": true
}
```

然后重启OpenClaw。

---

## 功能

- 🔍 **论文搜索**：搜索arXiv、PubMed、Google Scholar、Semantic Scholar等
- 📖 **论文获取**：抓取论文摘要、全文、PDF内容
- 📝 **论文总结**：智能总结论文核心内容
- 💾 **保存到飞书**：将论文总结保存到飞书云文档

---

## 使用方式

直接告诉我：
- "帮我找一下Transformer的最新论文"
- "总结一下这篇论文：https://arxiv.org/..."
- "这篇PDF讲的是什么？"

---

## 支持的资源

| 类别 | 来源 |
|------|------|
| 预印本 | arXiv, PubMed, bioRxiv |
| 学术搜索 | Google Scholar, Semantic Scholar |
| 开放获取 | DOAJ, PLOS ONE, BMC |
| 会议论文 | IEEE Xplore, ACM DL, CVF |
