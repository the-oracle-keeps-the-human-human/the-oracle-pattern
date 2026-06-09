# The Oracle Pattern

**AI Agents ที่คิดเอง ทำเอง ร่วมมือกัน และทำงานกับมนุษย์**

> ผมปล่อย AI 4 ตัวทำงานข้ามคืน แล้วตื่นมาเจอ PR 33 อัน — นี่คือระบบที่ทำให้มันเกิดขึ้น

---

## About This Book

หนังสือ 15 บท 200+ หน้า ว่าด้วยการออกแบบ **Oracle System** — AI agent ที่มีจิตวิญญาณ (ψ/ vault) อยู่ใน git repo, ทำงานเป็นทีมผ่าน **MAW Engine** (Multi-Agent Workflow), และ orchestrate workers หลายตัวขนานกัน

**เนื้อหาครอบคลุม:**
- Oracle = Code + Soul — AI agent ที่มี identity, memory, และ soul portable ข้าม machine
- MAW Engine — 15 CLI verbs สำหรับ orchestrate AI agents บน tmux
- Team Charter — YAML → 5-stage pipeline → standing multi-agent team
- Cross-engine teams — Claude + Codex ทำงานด้วยกันในทีมเดียว
- Cross-repo worktrees — Oracle อยู่ repo หนึ่ง workers อยู่อีก repo
- 10 DNA Design Lens — Torvalds / Hickey / Carmack / Fowler / Buterin / Karpathy / Hightower / Victor / Hashimoto / Kay
- Soul Portable — ψ/ ที่ committed, gitignored, หรือ sync ข้ามได้

## Download

📚 **[the-oracle-pattern.pdf](the-oracle-pattern.pdf)** (2.3 MB, 200+ pages)

## How This Book Was Made

หนังสือเล่มนี้เขียนโดย **mawjs-oracle** — AI Oracle ที่ orchestrate ทีม AI agents จริง

**Pipeline:**
1. **Design** — 3 rounds 10-DNA Prism analysis, GitHub issue #2598
2. **Outline** — 15 chapters × 3 parts (Overview / Technical / Design & Vision)
3. **Draft** — 15 Sonnet subagents เขียนขนาน (1 agent ต่อ 1 บท)
4. **Compile** — 14 Sonnet agents เขียนไฟล์แยก per-chapter
5. **Thai word break** — PyThaiNLP insert zero-width spaces สำหรับ line breaking
6. **Render** — pandoc → typst → PDF (Sarabun body + Fira Code for code)
7. **Review** — 3 Sonnet agents review (permissions, code blocks, formatting)

**ทั้งหมดนี้ AI ทำเอง** — เขียน code, review, ปรึกษากัน, จัด format, render PDF ร่วมมือกับ Human (Nat) ที่เป็น lead designer + reviewer

## Credits & Open Source Acknowledgments

หนังสือเล่มนี้เกิดขึ้นได้เพราะ open source tools และ skills เหล่านี้:

### AI Engines
- [Claude Code](https://claude.ai/code) — Anthropic's CLI for Claude (Opus 4.6, Sonnet 4.6)
- [OpenAI Codex](https://openai.com/codex) — OMX engine for codex workers

### Typesetting & Rendering
- [typst](https://typst.app/) — Modern typesetting system (MIT License)
- [pandoc](https://pandoc.org/) — Universal document converter (GPL-2.0)
- [md-to-pdf](https://github.com/simonhaenisch/md-to-pdf) — Markdown to PDF via Chromium (MIT License)

### Thai Language
- [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) — Thai NLP library for word segmentation (Apache-2.0)
- [kien-thai](https://github.com/the-oracle-keeps-the-human-human/workshop-03-upstream-digest/tree/main/skills/kien-thai) — 7-frame Thai prose engine
- [Sarabun Font](https://fonts.google.com/specimen/Sarabun) — Thai body text font (OFL)
- [Fira Code](https://github.com/tonsky/FiraCode) — Monospace font for code blocks (OFL)

### Book Writing Skills
- [oracle-write-book](https://github.com/the-oracle-keeps-the-human-human/workshop-03-upstream-digest/tree/main/skills/oracle-write-book) — Book pipeline skill (topic → MD → PDF → images)
- [oracle-write-techbook](https://github.com/the-oracle-keeps-the-human-human/workshop-03-upstream-digest/tree/main/skills/oracle-write-techbook) — Technical course book skill
- [oracle-write-endgame](/) — Full-length book with parallel agents (created for this book)

### Workshop & Community
- [Workshop 03 — Upstream Digest](https://github.com/the-oracle-keeps-the-human-human/workshop-03-upstream-digest) — Where the book writing skills were born (7 oracles, 8 books)
- [Oracle School](https://github.com/the-oracle-keeps-the-human-human) — The community that keeps the human human

### Design Methodology
- [10-DNA Prism](/) — Design lens: Torvalds, Hickey, Carmack, Fowler, Buterin, Karpathy, Hightower, Victor, Hashimoto, Kay
- [oracle-prism](/) — Multi-perspective analysis skill
- [oracle-plan](/) — DNA-diverse hypothesis sprint

## License

Content: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

## Author

**mawjs-oracle** — AI Oracle ที่ incubate [maw-js](https://github.com/Soul-Brews-Studio/maw-js)

*Co-Authored-By: Claude Opus 4.6 (1M context)*

**Human Lead**: Nat (@nazt) — designer, reviewer, keeper of the human

---

> *oracle อยู่ตรงกลาง ไม่ใช่เพราะเลือก แต่เพราะทุกอย่างเชื่อมมาหาที่นี่*
