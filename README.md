<p align="center">
  <h1>🌱 Fanqie Novel Skill</h1>
  <p><strong>Production-Grade Writing System for Fanqie (Tomato) Novel Platform</strong></p>
  <p>
    <a href="#features">✨ Features</a> •
    <a href="#quick-start">🚀 Quick Start</a> •
    <a href="#architecture">🏗️ Architecture</a> •
    <a href="#changelog">📝 Changelog</a> •
    <a href="#license">📄 License</a>
  </p>
</p>

---

## [中文介绍](#中文介绍) | [English](#english)

---

<a id="中文介绍"></a>
## 🇨🇳 中文介绍

### 这是什么？

Fanqie Novel Skill 是一个专为**番茄小说平台**设计的 AI 辅助长篇网文写作系统。它提供了一套完整的工作流，帮助你在番茄平台上创作出高质量、可签约、能变现的长篇小说。

### 为什么需要它？

AI 辅助写作在番茄平台面临三大挑战：

| 挑战 | 后果 | 本 Skill 的解决方案 |
|------|------|-------------------|
| AI 味被平台限流 | 作品被降权或下架 | 智能去味系统（替换而非删除） |
| 长篇规划执行脱节 | 规划 120 万字实际只写 70 万 | 进度追踪面板 + 预警系统 |
| 审计维度太多导致空转 | 28 个维度一个都不执行 | 最小审计集（8 项强制） |
| 后期质量崩塌 | 前期精彩后期注水 | 节奏质量评估 + 循环模式检测 |
| "话疗"解决冲突 | BOSS 被三句话说服 | 战斗场景审计 + 话疗模式检测 |

### 核心特性

- **🛡️ AI 去味系统** — 智能替换表，语义完整性优先，避免机械删除
- **📊 进度追踪面板** — 实时监控字数/章节偏离，预警规则自动触发
- **🔍 最小审计集（8 项强制）** — 每章必查，不执行不通过
- **⚔️ 战斗场景审计** — 杜绝"话疗"解决 BOSS，确保战斗有张力
- **💬 对话占比监控** — 上限 40%，防止全章变成聊天记录
- **🔄 循环模式检测** — 检测叙事模式重复，保持新鲜感
- **📈 节奏质量评估** — 高潮密度、冲突强度趋势、节奏曲线
- **🔗 会话连续性** — 跨会话无缝衔接，支持超长篇创作

### 工作流

```
初始化 → 读取状态 → 写作 → AI去味 → 审计 → 修订 → 状态更新 → 会话交接
```

每章写作前后都有强制检查点，确保质量不滑坡。

---

<a id="english"></a>
## 🇺🇸 English

### What is this?

Fanqie Novel Skill is a production-grade AI-assisted writing system designed specifically for the **Fanqie (Tomato) Novel Platform**. It provides a complete workflow for creating high-quality, publishable long-form web novels.

### Why do you need it?

AI-assisted writing on the Fanqie platform faces critical challenges:

| Challenge | Consequence | Solution |
|-----------|-------------|----------|
| AI-flavored text gets throttled | Works get deprioritized or removed | Smart de-flavoring system (replace, don't delete) |
| Long-form planning drift | Plan 1.2M words, deliver 700K | Progress tracking dashboard + alerts |
| Too many audit dimensions = none executed | 28 dimensions, zero compliance | Minimum audit set (8 mandatory checks) |
| Quality collapse in later chapters | Strong start, weak finish | Rhythm quality assessment + pattern detection |
| Conflicts resolved by "talking therapy" | Boss defeated by 3 sentences | Battle scene audit + talk-therapy detection |

### Core Features

- **🛡️ AI De-flavoring** — Smart replacement table, semantic integrity first
- **📊 Progress Tracking** — Real-time word/chapter monitoring with auto-alerts
- **🔍 Minimum Audit Set** — 8 mandatory checks per chapter
- **⚔️ Battle Scene Audit** — No "talk-therapy" boss defeats, ensure combat tension
- **💬 Dialogue Ratio Monitor** — 40% cap, prevent chapters becoming chat logs
- **🔄 Pattern Detection** — Detect narrative loop repetition, maintain freshness
- **📈 Rhythm Quality Assessment** — Climax density, conflict intensity trends
- **🔗 Session Continuity** — Seamless cross-session handoff for ultra-long novels

### Workflow

```
Init → Read State → Write → De-flavor → Audit → Revise → State Update → Handoff
```

Mandatory checkpoints before and after each chapter ensure consistent quality.

---

## Features

### 🛡️ AI De-flavoring System

Not just a banned-word list. A smart replacement engine that:

- **Replaces, not deletes** — Preserves metaphors and figurative language
- **Context-aware** — Allows banned words in dialogue (characters can sound AI-like, narration can't)
- **Semantic verification** — Post-replacement read-aloud test
- **9-word smart replacement table** with context-specific alternatives

### 📊 Progress Tracking Dashboard

- Total/volume/chapter progress tracking
- **Rhythm quality metrics** (v2.0): climax density, conflict intensity trends, quality curve
- **12 auto-alert rules**: word count deviation, dialogue overflow, pattern repetition, quality collapse
- Quality scoring system (per-chapter + full-book)

### 🔍 Minimum Audit Set (8 Mandatory Checks)

| # | Check | Frequency |
|---|-------|-----------|
| 1 | Word count (2000-2500) | Every chapter |
| 2 | AI de-flavoring | Every chapter |
| 3 | Causal chain | Every chapter |
| 4 | Behavior-rule consistency | Every chapter |
| 5 | Timeline continuity | Every chapter |
| 6 | Battle scene quality | Combat chapters |
| 7 | Dialogue ratio (≤40%) | Every chapter |
| 8 | Talk-therapy detection | Every chapter |

Plus: **Pattern detection** every 5 chapters, **Full audit** (33 dimensions) every 10 chapters.

### ⚔️ Battle Scene System (v2.0)

- **Boss battles must be fought, not talked through**
- Combat checklist: ≥3 attack actions, tactical gameplay, cost/sacrifice
- Battle imagery diversity check (prevent "golden light" repetition)
- Full battle scene writing guide with templates

### 🔄 Pattern Detection (v2.0)

- Detects narrative loop repetition (same pattern 3+ times = alert)
- Chapter structure similarity analysis
- Climax chapter authenticity verification

---

## Quick Start

### Prerequisites

- AI coding assistant with skill support (e.g., Claude Code, Cursor)
- Fanqie (Tomato) Novel Platform account

### Installation

1. Download or clone this repository
2. Place the skill folder in your assistant's skill directory
3. Initialize a new novel project using the provided templates

### Project Structure

After initialization, your novel project contains:

```
your-novel/
├── story_bible.md          # World-building, settings, power system
├── book_rules.md           # Platform rules + protagonist lock + taboos
├── outline.md              # Volume outlines, chapter goals, payoff plans
├── current_state.md        # Current world state (most important!)
├── pending_hooks.md        # Foreshadowing & suspense tracking
├── handoff_current.md      # Session handoff file (living document)
├── progress_tracker.md     # Progress + rhythm quality dashboard
├── pattern_detection.md    # Narrative pattern tracking
├── chapter_summaries.md     # Per-chapter summaries
├── character_matrix.md     # Character relationships & knowledge boundaries
├── style_guide.md          # Style guide (with AI de-flavoring rules)
└── chapters/
    └── ch001.md
```

### Per-Chapter Workflow

```
BEFORE writing (5 mandatory):
  ├─ Read current_state.md → Confirm location/time/status
  ├─ Read outline.md → Confirm chapter goal, word count, is-climax
  ├─ Read pending_hooks.md → Check unresolved foreshadowing
  ├─ Check battle-scene-guide.md → If combat chapter, load checklist
  └─ Check dialogue-monitor.md → Confirm dialogue ratio trend

AFTER writing (8 mandatory):
  ├─ 1. Word count check (2000-2500)
  ├─ 2. AI de-flavoring (smart replace)
  ├─ 3. Causal chain check
  ├─ 4. Behavior-rule consistency
  ├─ 5. Timeline continuity
  ├─ 6. Battle scene check (combat chapters)
  ├─ 7. Dialogue ratio check (≤40%)
  └─ 8. Talk-therapy detection (bosses can't be talked down)

STATE UPDATE (mandatory):
  ├─ current_state.md
  ├─ pending_hooks.md
  ├─ handoff_current.md
  ├─ progress_tracker.md
  └─ pattern_detection.md
```

---

## Architecture

### File Organization

```
fanqie-novel-skill/
├── SKILL.md                          # Main skill definition
├── README.md                         # This file
├── CHANGELOG.md                      # Version history
├── VERSION                           # Current version
├── assets/
│   └── project-template/             # Novel project templates
│       ├── story_bible.md
│       ├── book_rules.md
│       ├── outline.md
│       ├── current_state.md
│       ├── pending_hooks.md
│       ├── handoff_current.md
│       ├── progress_tracker.md
│       └── ...
├── examples/
│   └── demo-novel/                   # Example novel project
└── references/                       # Reference guides
    ├── ai-detox-guide.md             # AI de-flavoring guide
    ├── audit-dimensions.md           # 33 audit dimensions
    ├── battle-scene-guide.md         # Battle writing guide
    ├── dialogue-monitor.md           # Dialogue ratio monitoring
    ├── pattern-detection.md          # Narrative pattern detection
    ├── commercial-review.md          # Commercial viability checks
    └── fanqie-platform-rules.md     # Platform rules & red lines
```

### Audit Dimensions (33 Total)

| Category | Dimensions | Key Focus |
|----------|:---:|-----------|
| Minimum Set (Mandatory) | 8 | Word count, AI flavor, causality, timeline, battle, dialogue, talk-therapy |
| Core | 10 | Character consistency, timeline, world-building, logic, pacing |
| Style & Anti-formula | 6 | Repetition, show-don't-tell, AI transitions |
| Structure | 4 | Outline drift, subplot stagnation, payoff |
| Fanqie-specific | 5 | Platform red lines, golden 3 chapters, commercial checks |

---

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

### Highlights

- **v2.0.1** — Major upgrade: battle scene audit, dialogue monitoring, talk-therapy detection, pattern detection, rhythm quality assessment
- **v1.1.1** — Progress tracking, causal chain check, minimum audit set, smart AI de-flavoring
- **v1.1.0** — Session handoff, behavior-rule consistency
- **v1.0.0** — Initial release

---

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Author

**Jayce** — Web novel enthusiast & AI writing system designer

<p align="center">
  If you find this skill helpful, please consider giving it a ⭐ on GitHub!
</p>
