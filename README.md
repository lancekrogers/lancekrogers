# Lance Rogers

Building AI systems that do what I want, the way I want them to.

## What I'm Building

### Festival Methodology + fest CLI
**File-based agent operating system**

Most AI tools give agents a chat window and hope for the best. Festival gives them a structured workspace they can actually navigate.

It's a hierarchical, file-based methodology where agents learn how to operate through `fest understand` commands, then use `fest execute` and `fest next` to know what to do at each step. The methodology itself teaches agents:

- What files to read (FESTIVAL_GOAL.md, CONTEXT.md, current task)
- When to read them (just-in-time, not upfront)
- How to make decisions (autonomy levels: High/Medium/Low)
- Where to document progress (CONTEXT.md for decisions, TODO.md for status)
- When work is actually complete (quality gates)

**[fest CLI](https://github.com/lancekrogers/festival-methodology/tree/main/fest)** is the agent interface:

- `fest understand` – Teaches agents the methodology (workflow, structure, rules)
- `fest execute` – Shows agents what to do now
- `fest next` – Tells agents what comes after current task
- File integrity via SHA256 checksums
- Smart navigation (fgo) between festivals and projects
- Config repos for team-specific templates/policies
- Quality gate automation
- Plugin system for custom commands

**The breakthrough:** Agents can work autonomously for days instead of minutes because the file structure + CLI commands replace constant human guidance. The methodology is self-documenting through `fest understand`, and the hierarchy (Festival → Phase → Sequence → Task) keeps them oriented.

---

### Agent Orchestration Infrastructure
**Breaking the linear constraint**

Building infrastructure where multiple agents coordinate on complex, multi-stage work. Moving beyond "one agent, one task" to systems that enable nonlinear scaling of autonomous operations.

---

### Claude Code Go SDK
**First unofficial SDK for Anthropic's Claude Code CLI (27⭐)**

Built in <1 week post-launch. Taught me that autonomous agents need fundamentally different infrastructure than human-driven workflows—which led directly to Festival Methodology.

---

**Currently:** Deep in production agent systems. Building infrastructure for teams of 1000+ agents that actually work together.

**Focus:** File-based agent coordination • Self-documenting methodologies • Autonomous execution at scale

🌐 [lance@blockhead.consulting](mailto:lance@blockhead.consulting)
