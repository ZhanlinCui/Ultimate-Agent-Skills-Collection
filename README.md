# 🚀 Ultimate Agent Skills Collection

<div align="center">

<img src="https://img.shields.io/badge/Skills-40+-blueviolet?style=for-the-badge" alt="Skills Count" />
<img src="https://img.shields.io/badge/Quality-Premium-gold?style=for-the-badge" alt="Quality" />
<img src="https://img.shields.io/badge/Claude%20AI-Compatible-00A67E?style=for-the-badge" alt="Claude Compatible" />

**The Most Comprehensive High-Quality Agent Skills Collection on the Internet**

[中文文档](./README.zh-CN.md) | [日本語ドキュメント](./README.ja.md)

</div>

---

## 📖 What Are Skills?

Skills are folders of instructions, scripts, and resources that AI agents load dynamically to improve performance on specialized tasks. They teach Claude (or other AI agents) how to complete specific tasks in a repeatable way—whether that's creating documents, analyzing data, automating workflows, or building applications.

## 🌟 Why This Collection?

This is the **most comprehensive curated collection** of high-quality agent skills gathered from across the internet, including:

- ✅ **40+ Premium Skills** covering creative, technical, and enterprise workflows
- ✅ **Production-Ready** - These skills power real applications
- ✅ **Well-Documented** - Each skill includes detailed instructions and examples
- ✅ **Organized by Category** - Easy to find what you need

---

## 📂 Skills Directory

### 🎨 Creative & Design

| Skill | Description |
|-------|-------------|
| **[algorithmic-art](./algorithmic-art/)** | Create generative art using p5.js with seeded randomness and interactive parameter exploration |
| **[canvas-design](./canvas-design/)** | Create beautiful visual art in .png and .pdf documents using design philosophy |
| **[frontend-design](./frontend-design/)** | Build distinctive, production-grade frontend interfaces with exceptional design quality |
| **[brand-guidelines](./brand-guidelines/)** | Apply official brand colors and typography to artifacts |
| **[theme-factory](./theme-factory/)** | Style artifacts with 10+ pre-set themes or generate custom themes on-the-fly |
| **[slack-gif-creator](./slack-gif-creator/)** | Create animated GIFs optimized for Slack with proper constraints |

### 📄 Document Skills

| Skill | Description |
|-------|-------------|
| **[docx](./docx/)** | Comprehensive Word document creation, editing with tracked changes and comments |
| **[pdf](./pdf/)** | PDF manipulation - extract text/tables, create, merge/split, handle forms |
| **[pptx](./pptx/)** | PowerPoint presentation creation, editing, layouts, and speaker notes |
| **[xlsx](./xlsx/)** | Spreadsheet creation, editing with formulas, formatting, and data analysis |
| **[doc-coauthoring](./doc-coauthoring/)** | Structured workflow for co-authoring documentation and proposals |
| **[internal-comms](./internal-comms/)** | Write internal communications: status reports, newsletters, FAQs, incident reports |
| **[github-release-assistant](./github-release-assistant/)** | Generate bilingual GitHub release documentation (English + Chinese) |

### 🛠️ Development & Technical

| Skill | Description |
|-------|-------------|
| **[mcp-builder](./mcp-builder/)** | Create high-quality MCP (Model Context Protocol) servers for LLM integrations |
| **[webapp-testing](./webapp-testing/)** | Test local web applications using Playwright with screenshots and logs |
| **[web-artifacts-builder](./web-artifacts-builder/)** | Build complex HTML artifacts with React, Tailwind, and shadcn/ui |
| **[skill-creator](./skill-creator/)** | Guide for creating effective skills that extend Claude's capabilities |
| **[deploying-to-production](./deploying-to-production/)** | Automate GitHub repository creation and Vercel deployment |
| **[internationalizing-websites](./internationalizing-websites/)** | Add multi-language support to Next.js with proper SEO configuration |

### 🔍 SEO & Performance

| Skill | Description |
|-------|-------------|
| **[google-official-seo-guide](./google-official-seo-guide/)** | Official Google SEO guide: search optimization, crawling, indexing best practices |
| **[web-performance-seo](./web-performance-seo/)** | Fix PageSpeed/Lighthouse accessibility errors for SEO optimization |

### 🧠 Planning & Workflow

| Skill | Description |
|-------|-------------|
| **[planning-with-files](./planning-with-files/)** | Manus-style file-based planning with task_plan.md, findings.md, progress.md |
| **[writing-plans](./writing-plans/)** | Create structured plans for multi-step tasks before coding |
| **[executing-plans](./executing-plans/)** | Execute written implementation plans with review checkpoints |
| **[brainstorming](./brainstorming/)** | Explore user intent, requirements and design before implementation |
| **[chat-compactor](./chat-compactor/)** | Generate session summaries for AI agent continuity across sessions |

### 🐛 Debugging & Quality

| Skill | Description |
|-------|-------------|
| **[systematic-debugging](./systematic-debugging/)** | Systematic approach to debugging: root cause analysis before fixes |
| **[test-driven-development](./test-driven-development/)** | TDD workflow: write tests first, then implementation |
| **[verification-before-completion](./verification-before-completion/)** | Verify work is complete before claiming success |
| **[receiving-code-review](./receiving-code-review/)** | Handle code review feedback with technical rigor |
| **[requesting-code-review](./requesting-code-review/)** | Request thorough code reviews for completed work |

### 🤖 Agent Orchestration

| Skill | Description |
|-------|-------------|
| **[dispatching-parallel-agents](./dispatching-parallel-agents/)** | Dispatch 2+ independent tasks to parallel subagents |
| **[subagent-driven-development](./subagent-driven-development/)** | Execute plans with specialized subagents for each task |
| **[using-superpowers](./using-superpowers/)** | Establish how to find and use skills in conversations |
| **[writing-skills](./writing-skills/)** | Create, edit, and verify skills before deployment |

### 🔧 Git & Development Workflow

| Skill | Description |
|-------|-------------|
| **[using-git-worktrees](./using-git-worktrees/)** | Create isolated git worktrees for feature development |
| **[finishing-a-development-branch](./finishing-a-development-branch/)** | Guide completion: merge, PR, or cleanup options |

### 🔗 Integration & Automation

| Skill | Description |
|-------|-------------|
| **[notebooklm](./notebooklm/)** | Query Google NotebookLM for source-grounded answers via browser automation |
| **[x-article-publisher](./x-article-publisher/)** | Publish Markdown articles to X (Twitter) Articles with proper formatting |
| **[doc-sync-tool](./doc-sync-tool/)** | Auto-sync Agents.md, claude.md, gemini.md files across projects |

---

## 🚀 How to Use

### In Claude.ai

1. Go to Project Settings → Skills
2. Upload the skill folder or individual `SKILL.md` files
3. Claude will automatically detect when to use each skill

### In Claude Code

```bash
# Register as plugin marketplace
/plugin marketplace add your-skills-repo

# Or install directly
/plugin install skill-name@your-marketplace
```

### In Claude API

Use skills via the Claude API following the [Skills API Quickstart](https://docs.claude.com/en/api/skills-guide).

---

## 📁 Skill Structure

Each skill follows this standard structure:

```
skill-name/
├── SKILL.md          # Main instructions (required)
├── scripts/          # Helper scripts (optional)
├── templates/        # Template files (optional)
├── references/       # Documentation (optional)
└── examples/         # Usage examples (optional)
```

The `SKILL.md` file contains:

```markdown
---
name: skill-name
description: When to use this skill and what it does
---

# Skill Name

[Instructions for Claude to follow]
```

---

## 🏷️ Skill Categories Quick Reference

| Category | Count | Examples |
|----------|-------|----------|
| 🎨 Creative & Design | 6 | algorithmic-art, frontend-design, theme-factory |
| 📄 Document Skills | 7 | docx, pdf, pptx, xlsx |
| 🛠️ Development | 6 | mcp-builder, webapp-testing, skill-creator |
| 🔍 SEO & Performance | 2 | google-official-seo-guide, web-performance-seo |
| 🧠 Planning & Workflow | 5 | planning-with-files, chat-compactor |
| 🐛 Debugging & Quality | 5 | systematic-debugging, test-driven-development |
| 🤖 Agent Orchestration | 4 | dispatching-parallel-agents, subagent-driven-development |
| 🔧 Git & Workflow | 2 | using-git-worktrees, finishing-a-development-branch |
| 🔗 Integration | 3 | notebooklm, x-article-publisher |

---

## 📜 License

Skills in this collection are provided under various licenses. Please check individual skill folders for specific license information.

---

## 🤝 Contributing

We welcome contributions! To add a new skill:

1. Create a folder following the skill structure
2. Include a comprehensive `SKILL.md`
3. Add any necessary scripts or templates
4. Submit a pull request

---

## ⭐ Star History

If you find this collection useful, please give it a star! ⭐

---

<div align="center">

**Made with ❤️ for the AI Agent Community**

*The Ultimate Collection of High-Quality Agent Skills*

</div>
