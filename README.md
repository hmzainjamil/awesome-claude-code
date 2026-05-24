# awesome-claude-code

> **Curated list of tools, skills, plugins, integrations, and resources for Claude Code developers** — the definitive reference for the Claude Code ecosystem

<p align="center">
  <a href="https://github.com/hmzainjamil/awesome-claude-code/stargazers"><img src="https://img.shields.io/github/stars/hmzainjamil/awesome-claude-code?style=for-the-badge&labelColor=555&color=yellow" alt="Stars"/></a>
  <a href="https://github.com/hmzainjamil/awesome-claude-code/network/members"><img src="https://img.shields.io/github/forks/hmzainjamil/awesome-claude-code?style=for-the-badge&labelColor=555&color=blue" alt="Forks"/></a>
  <a href="https://github.com/hmzainjamil/awesome-claude-code/issues"><img src="https://img.shields.io/github/issues/hmzainjamil/awesome-claude-code?style=for-the-badge&labelColor=555&color=red" alt="Issues"/></a>
  <a href="https://github.com/hmzainjamil/awesome-claude-code/pulls"><img src="https://img.shields.io/github/issues-pr/hmzainjamil/awesome-claude-code?style=for-the-badge&labelColor=555&color=purple" alt="PRs"/></a>
  <a href="https://github.com/hmzainjamil/awesome-claude-code/commits/main"><img src="https://img.shields.io/github/last-commit/hmzainjamil/awesome-claude-code?style=for-the-badge&labelColor=555&color=green" alt="Last Commit"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Awesome-list-red?style=flat&labelColor=555&logo=awesome"/>
  <img src="https://img.shields.io/badge/Claude_Code-ecosystem-blue?style=flat&labelColor=555"/>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat&labelColor=555"/>
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat&labelColor=555"/>
</p>

---

## Why This Exists

The Claude Code ecosystem is growing fast — skills, plugins, MCP servers, agents, GUIs, workflows, frameworks. This list aggregates the best tools and resources in one place so developers spend time building, not searching. Every listing has been evaluated for production use.

---

## At a Glance

| Section | Count | Quality |
|---|---|---|
| Official Anthropic resources | 10+ | Authoritative |
| Agents & orchestration | 30+ | 🔥 >1000 stars for top entries |
| Claude Skills | 50+ | Production tested |
| Claude Plugins | 20+ | MCP or native |
| Tools & Utilities | 40+ | Active maintenance |
| IDE integrations | 15+ | VS Code, Cursor, JetBrains |
| Clients & GUIs | 10+ | Alternative frontends |
| Infrastructure | 15+ | Proxies, load balancers |
| SDKs & DevKits | 10+ | Multiple languages |
| Guides & Learning | 20+ | Tutorials + deep dives |

---

## 🧠 CONCEPTS

| Concept | Description |
|---|---|
| **Claude Code** | Anthropic's official CLI for Claude — terminal-based agentic coding |
| **Skill** | SKILL.md expertise package — loadable domain knowledge |
| **Plugin** | Tool integration — MCP server or native extension |
| **MCP** | Model Context Protocol — standard for AI↔tool communication |
| **CLAUDE.md** | Project instructions file — read at every session start |
| **Hook** | Script triggered before/after tool execution |
| **Agent** | Specialized sub-process Claude can spawn |
| **Context window** | 200K token limit — management is critical for long sessions |
| **Slash command** | Custom `/command` defined in `~/.claude/commands/` |
| **Star tier** | 🔥 >1000 stars, 🌟 >500 stars, ✨ >100 stars |

### 🔥 Hot

- **Task Master** — 20K+ stars, the definitive task management system for Claude Code projects
- **claude-skills** — 5200+ stars, 235 production skills for 11 agents
- **caveman-prompt-compression** — viral token reduction — 75% output savings
- Source → [HMZ](https://github.com/hmzainjamil)

---

## ⚙️ HOW IT WORKS

This is a curated list — not a tool itself. Use it to discover resources, then follow installation instructions from each listing's repository.

**Finding resources:**
```bash
# Search list by technology
grep -i "kubernetes" README.md

# Search by use case
grep -i "token" README.md

# Get top-rated items
grep "🔥" README.md
```

---

## 🚀 INSTALL

```bash
# Clone for local search
git clone https://github.com/hmzainjamil/awesome-claude-code

# Grep for resources
grep -i "MCP" awesome-claude-code/README.md

# Or read online:
# https://github.com/hmzainjamil/awesome-claude-code
```

---

## 📟 USAGE

```bash
# Quick find
grep -n "seo" README.md | head -20

# Find by category
sed -n '/## Skills/,/## Plugins/p' README.md

# Find starred repos
grep "🔥\|🌟\|✨" README.md
```

---

## ⚙️ CONFIGURATION

| Listing standard | Requirement |
|---|---|
| Active maintenance | Last commit < 6 months |
| Documentation | README with install instructions |
| License | OSI-approved license required |
| Production use | Used in real projects |
| Star count shown | Static at time of submission |
| Breaking changes | Must document in CHANGELOG |

---

## 💡 TIPS AND TRICKS

### Discovery
1. **Star tier filter** — 🔥 entries are battle-tested with large communities. Start there. Source → [HMZ](https://github.com/hmzainjamil)
2. **Check last commit** — repos with no activity in 12+ months may have breaking changes with current Claude Code. Source → [HMZ](https://github.com/hmzainjamil)
3. **Read issues before installing** — 5 min reading open issues saves hours of debugging. Source → [HMZ](https://github.com/hmzainjamil)

### Organization
4. **Install by category** — install all DevOps resources at once rather than one-off. Source → [HMZ](https://github.com/hmzainjamil)
5. **Bookmark clusters** — group related resources: skills + MCP + agents for same domain. Source → [HMZ](https://github.com/hmzainjamil)
6. **Version pin** — when using a resource in production, note the commit hash. Source → [HMZ](https://github.com/hmzainjamil)

### Contributing
7. **Submit format** — `[Name](url) — one-line description` with star tier badge if applicable. Source → [HMZ](https://github.com/hmzainjamil)
8. **Quality bar** — only submit resources you've actually used in production. Source → [HMZ](https://github.com/hmzainjamil)
9. **Update stale entries** — if you notice a repo is archived/abandoned, open a PR to remove. Source → [HMZ](https://github.com/hmzainjamil)

### Advanced
10. **Cross-reference agents** — check [7 Best CLI AI Coding Agents](https://www.scriptbyai.com/best-cli-ai-coding-agents/) for alternatives to Claude Code. Source → [HMZ](https://github.com/hmzainjamil)
11. **Stack combinations** — best results: Task Master + claude-skills + caveman compression + MAE orchestration. Source → [HMZ](https://github.com/hmzainjamil)
12. **Context window math** — 200K tokens ÷ average response length = max turns per session. Source → [HMZ](https://github.com/hmzainjamil)

---

## 🔧 TROUBLESHOOTING

| Issue | Cause | Fix |
|---|---|---|
| Listed repo deleted | Repo removed by owner | Open PR to remove entry |
| Install instructions outdated | Repo API changed | Check repo's own README |
| Tool incompatible with Claude version | Breaking API change | Check release notes |
| MCP server not found | npm package renamed | Check package.json for new name |
| Skill format changed | Claude Code update | Check migration guide |

---

## 📊 ARCHITECTURE

This is a curated Markdown list. Structure:

```
awesome-claude-code/
├── README.md              # Main curated list
├── CONTRIBUTING.md        # Submission guidelines
├── code-of-conduct.md     # Community standards
└── scripts/
    └── validate.sh        # Link checker
```

---

## 🗺️ ROADMAP

- [ ] Search UI — filterable web interface for the list
- [ ] Automated link checking — weekly broken link detection
- [ ] Category pages — deep dives into each category
- [ ] Benchmarks — comparative performance of similar tools
- [ ] Newsletter — weekly new additions digest

---

## ☠️ STARTUPS / BUSINESSES

Claude Code is the productivity multiplier for engineering teams. This list is the onboarding guide — new team members find the right tools in minutes, not days of discovery.

**Agency onboarding:** send team members to this list first. By end of day 1 they have: task management, skills for their domain, MCP tools for their stack, and token optimization. No manual onboarding needed.

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/awesome-claude-code&type=Date)](https://star-history.com/#hmzainjamil/awesome-claude-code&Date)

---

<p align="center">
  Built by <a href="https://github.com/hmzainjamil">HMZ</a> · <a href="https://github.com/hmzainjamil/awesome-claude-code/issues">Issues</a> · <a href="https://github.com/hmzainjamil/awesome-claude-code/pulls">PRs</a>
</p>
