# Genesis 🧠

> The first brain of an AI agent.

**Genesis** is a lightweight, project-local memory and instruction system for AI agents.

It gives agents the context they need to **understand a project before they act**.

### Works with

* CLI Agents
* IDE Agents
* Coding Agents
* Autonomous Agents

### The Flow

```text
Genesis
   ↓
Understand
   ↓
Plan
   ↓
Execute
   ↓
Learn
   ↓
Remember
   ↺
```

### Structure

```text
.agents/
├── genesis.md          # Agent rules & workflow
└── agent_md/           # Persistent project knowledge
    ├── project-learn.md
    ├── user-learn.md
    ├── domains/
    ├── patterns/
    ├── decisions/
    └── debugging/
```

### Core Idea

> **Understand before acting. Learn while working. Remember for the next agent.**

Genesis keeps knowledge **project-local, human-readable, version-controlled, and agent-agnostic**.

The goal is simple:

**Every agent session should start smarter than the previous one.**
