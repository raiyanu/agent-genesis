# Genesis 🧠

> The first brain of an AI agent.

**Genesis** is a lightweight, project-local memory and instruction system for AI agents.

It gives agents the context they need to **understand a project before they act**.

It also enables **shared intelligence across developers, devices, and accounts**, ensuring that project knowledge is not lost with a single machine or session.

It also improves **agent / AI workflow speed by ~80%** by removing repeated discovery of project structure, patterns, and decisions.

---

### ⚠️ Important Usage Instruction

> The file `genesis.md` is the **entry point for all AI agents**.

You must:

* Copy `genesis.md` into your agent’s rule/config system **OR**
* Configure your agent to **always read ****`genesis.md`**** first before any task**

Without this step, Genesis will not function as intended.

---

### Works with

* CLI Agents
* IDE Agents
* Coding Agents
* Autonomous Agents

---

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

---

### Structure

```text
.agents/
├── genesis.md          # Agent rules & workflow (must be loaded first)
└── agent_md/           # Persistent project knowledge
    ├── project-learn.md
    ├── user-learn.md
    ├── domains/
    ├── patterns/
    ├── decisions/
    └── debugging/
```

---

### Core Idea

> **Understand before acting. Learn while working. Remember for the next agent.**

Genesis keeps knowledge **project-local, human-readable, version-controlled, and agent-agnostic**.

It also ensures that knowledge can be **shared seamlessly across different developers, devices, and accounts**, so every contributor and every agent starts with the same understanding of the project.

---

### Goal

**Every agent session should start smarter than the previous one — no matter who is working on the project or where they are working from.**
