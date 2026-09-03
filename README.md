<div align="center">

# 🍎 Apple & Emil UI/UX Design Engineering Skills

**A curated suite of agentic skills, design heuristics, and motion engineering principles for modern software.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status: Active](https://img.shields.io/badge/Status-Maintained-success.svg)]()

</div>

---

## 📖 Overview

This repository contains a comprehensive suite of **Design Engineering and Motion Design Skills** formulated for AI coding assistants (such as Antigravity, Claude Code, Cursor, Windsurf, and Copilot) as well as human developers and designers.

Building interfaces with high polish, deliberate motion, and physical tactility is challenging. AI models often lack intrinsic design taste—selecting linear easings for enter transitions, unnatural spring parameters, or jarring popover animations. This collection encodes proven rules, motion physics, and design craftsmanship into actionable, agent-readable instruction files.

---

## 📦 Skills Directory & Reference

| Skill | Path | Description |
|---|---|---|
| **🎨 emil-design-eng** | [`skills/emil-design-eng/SKILL.md`](./skills/emil-design-eng/SKILL.md) | Core UI polish guidelines, component design heuristics, and micro-interaction details. |
| **🍎 apple-design** | [`skills/apple-design/SKILL.md`](./skills/apple-design/SKILL.md) | Apple's Human Interface Guidelines, fluid gesture interactions, and WWDC motion principles adapted for the web. |
| **⚡ animate** | [`skills/animate/SKILL.md`](./skills/animate/SKILL.md) | Step-by-step decision framework to build animations from scratch (property selection, duration, easing, interrupts). |
| **🔍 review-animations** | [`skills/review-animations/SKILL.md`](./skills/review-animations/SKILL.md) | Strict critique and code review checklist for existing CSS/JS animations and spring physics. |
| **🛠️ improve-animations** | [`skills/improve-animations/SKILL.md`](./skills/improve-animations/SKILL.md) | Repository-wide animation audit that outputs prioritized, self-contained implementation plans. |
| **💡 find-animation-opportunities** | [`skills/find-animation-opportunities/SKILL.md`](./skills/find-animation-opportunities/SKILL.md) | Discover areas in your UI that will benefit from motion while rejecting unnecessary animations. |
| **📚 animation-vocabulary** | [`skills/animation-vocabulary/SKILL.md`](./skills/animation-vocabulary/SKILL.md) | Reverse-lookup glossary translating human descriptions into precise motion design terminology. |
| **📦 pick-ui-library** | [`skills/pick-ui-library/SKILL.md`](./skills/pick-ui-library/SKILL.md) | Intelligent UI component library recommendation based on battle-tested modern tools. |
| **🧪 prototype** | [`skills/prototype/SKILL.md`](./skills/prototype/SKILL.md) | Rapid UI variant generator with interactive switchers to compare multiple designs. |

---

## 🚀 How to Use

### 1. In AI Coding Assistants & Agents
Copy any skill folder (or the entire `skills/` directory) into your project's agent instructions folder (e.g. `.gemini/skills/`, `.claude/skills/`, or `.cursor/rules/`), or prompt your AI agent directly:

```text
Please read 'skills/apple-design/SKILL.md' and apply Apple interface guidelines and spring physics to this component.
```

### 2. Quick Installation via Skills CLI
```bash
npx skills@latest add emilkowalski/skills
```

---

## 🛠️ Design & Motion Philosophy

- **Natural Momentum & Physics:** Interfaces should react with weight, momentum, and appropriate damping rather than synthetic linear curves.
- **Interruption Over Rigidity:** Interactive transitions should be cancelable and continuous when user input changes mid-animation.
- **Visual Restraint:** Motion exists to clarify hierarchy, orient spatial position, and provide feedback—not to distract.
- **Subtle Layering:** Use semi-transparent shadows, dynamic borders, and backdrop blurs to establish depth without visual clutter.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
