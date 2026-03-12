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

# Academic Paper Reader

> 🎯 **One-line Description**: AI assistant for searching, reading, and summarizing academic papers

> 🌐 **语言 / Language**: [中文](./SKILL.md) | [English](./SKILL_EN.md)

---

## 🚀 One-Click Install (Recommended)

Just tell me:
```
Install academic-paper-reader skill (https://github.com/cszr-liuxiaobo/clawskills-all-in-one/tree/main/skills/academic-paper-reader)
```

I will automatically:
1. Read SKILL.md to understand the skill
2. Copy it to OpenClaw's skills directory
3. Enable it in the config file

---

## 📥 Manual Install

Add to `skills.entries` in `openclaw.json`:

```json
"academic-paper-reader": {
  "enabled": true
}
```

Then restart OpenClaw.

---

## Features

- 🔍 **Paper Search**: Search arXiv, PubMed, Google Scholar, Semantic Scholar, etc.
- 📖 **Paper Fetch**: Grab abstracts, full text, PDF content
- 📝 **Paper Summary**: Intelligently summarize paper core content
- 💾 **Save to Feishu**: Save paper summaries to Feishu cloud docs

---

## Usage

Just tell me:
- "Find me the latest papers on Transformers"
- "Summarize this paper: https://arxiv.org/..."
- "What is this PDF about?"

---

## Supported Resources

| Category | Sources |
|----------|---------|
| Preprints | arXiv, PubMed, bioRxiv |
| Academic Search | Google Scholar, Semantic Scholar |
| Open Access | DOAJ, PLOS ONE, BMC |
| Conference Papers | IEEE Xplore, ACM DL, CVF |
