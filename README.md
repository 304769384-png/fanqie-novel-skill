# 番茄小说写作Skill（Fanqie Novel Skill）

版本：**1.1.1**

**专为番茄小说平台打造的长篇网文写作操作系统。**

作者：**Jayce**

---

## 这是什么

一个面向番茄小说平台的长篇网文写作Skill，解决三个核心问题：

1. **长篇不跑偏**：通过Truth Files系统维护世界观、角色、伏笔、状态
2. **番茄能签约**：内置番茄平台规则、商业审查、付费转化检查
3. **AI没味道**：专项AI去味检查，避免被平台限流

---

## 核心工作流

```
init → write-next → draft → ai-detox → audit → revise → extract-state → state-update
```

---

## 适合谁

适合这些情况：

- 你想在番茄小说平台写长篇网文（120万字+）
- 你想让AI连续写很多章时不崩设定
- 你想通过番茄签约审核
- 你想避免AI味被平台限流

---

## 文件结构

```
fanqie-novel-skill/
├── SKILL.md                    # 核心说明文件
├── README.md                   # 本文件
├── VERSION                     # 版本号
├── references/                 # 参考文档
│   ├── fanqie-platform-rules.md    # 番茄平台规则
│   ├── ai-detox-guide.md           # AI去味专项指南
│   ├── commercial-review.md        # 商业审查指南
│   └── audit-dimensions.md         # 审计维度（番茄专用版）
└── assets/
    └── project-template/       # 项目模板
        ├── story_bible.md          # 世界观圣经
        ├── book_rules.md           # 平台规则+主角锁定
        ├── outline.md              # 四卷大纲
        ├── current_state.md        # 当前状态（最重要！）
        ├── pending_hooks.md        # 伏笔追踪
        ├── character_matrix.md     # 角色关系矩阵
        ├── chapter_summaries.md    # 章节摘要
        └── style_guide.md          # 风格指南（含AI去味）
```

---

## 快速开始

### 1. 初始化项目

复制 `assets/project-template/` 到你的项目文件夹。

### 2. 填充核心文件

按优先级填写：

1. `story_bible.md` - 世界观、设定
2. `book_rules.md` - 平台规则、主角锁定
3. `outline.md` - 四卷大纲
4. `character_matrix.md` - 角色设定

### 3. 开始写作

每章写前阅读：
- `story_bible.md`
- `book_rules.md`
- `current_state.md`
- `pending_hooks.md`

### 4. 写后检查

每章写后执行：
1. AI去味检查（`references/ai-detox-guide.md`）
2. 审计检查（`references/audit-dimensions.md`）
3. 商业检查（`references/commercial-review.md`）

### 5. 更新状态

每章通过后更新：
- `current_state.md`
- `pending_hooks.md`
- `chapter_summaries.md`

---

## 番茄专用功能

### 平台红线检查

- 是否标注"AI辅助创作"？
- 是否有敏感内容？
- 是否有抄袭/洗稿？
- 是否有重复注水？

### 生死线检查

- 前300字：主角+核心事件
- 前1000字：身份+金手指+冲突
- 第一章末：钩子
- 前三章：核心能力+目标+悬念

### AI去味检查

- 排比三连
- 空洞抒情
- 万能过渡
- 万能形容词
- 情感标签

### 商业审查

- 黄金三章
- 爽点引擎
- 付费转化
- 签约节点

---

## 设计目标

这个Skill不是魔法小说生成器。它是一个**纪律层**，让长篇AI写作更稳定、可检查、可维护，同时**专门适配番茄小说平台**。

**记住：新人赚钱的核心 = 过签约 + 稳日更 + 去 AI 味 + 抓读者。**

---

## 版本历史

| 版本 | 日期 | 更新内容 |
|------|------|---------|
| 1.0.0 | 2026-05-08 | 初始版本，番茄专用写作系统 |

---

## 作者

**Jayce**
