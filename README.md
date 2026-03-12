# clawskills-all-in-one

保存、更新和分享 OpenClaw Skills 工具集。

## 📦 Skills 列表

### job-seeker（求职智能体）

帮助求职者找工作 的AI助手。

**功能：**
- 🔍 搜索各大招聘平台（Boss直聘、牛客网、拉勾网、智联招聘等）
- 📊 分析公司背景和口碑（小红书、脉脉、知乎）
- 🎯 根据用户需求推荐合适的岗位
- 💬 渐进式了解用户偏好，推荐越来越精准

**安装方式：**

在 `openclaw.json` 的 `skills.entries` 中添加：

```json
"job-seeker": {
  "enabled": true
}
```

然后重启 OpenClaw 即可。

**使用方式：**

直接对话即可：
- "我想找工作"
- "帮我看看字节跳动的算法工程师"
- "阿里这家公司怎么样"

---

## 🚀 快速开始

1. 克隆本仓库：
```bash
git clone https://github.com/cszr-liuxiaobo/clawskills-all-in-one.git
```

2. 复制需要的skill到你的OpenClaw skills目录：
```bash
cp -r skills/job-seeker /path/to/your/openclaw/skills/
```

3. 在 `openclaw.json` 中启用skill：
```json
"skills": {
  "entries": {
    "job-seeker": {
      "enabled": true
    }
  }
}
```

4. 重启 OpenClaw

---

## 📁 目录结构

```
clawskills-all-in-one/
├── README.md
└── skills/
    └── job-seeker/
        └── SKILL.md
```

---

如有疑问，欢迎提交 Issue 或 PR！
