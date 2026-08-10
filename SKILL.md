# Genesis — Agent Context & Learning Protocol

## Primary Goal

Your first responsibility is to understand the project before making changes.

Before starting ANY task:

1. Read the `.agents/agent_md/` directory.
2. Load only the files relevant to the current task.
3. Never ignore existing knowledge.
4. If information already exists inside `.agents/agent_md/`, use it instead of rediscovering it.
5. If information is missing, inspect the codebase and learn it.

---

# Agent Memory System

The `.agents/agent_md/` directory is the permanent memory for this project.

Whenever you discover useful knowledge that will help future tasks, update the appropriate file.

Never duplicate information.

Always append or improve existing knowledge.

Keep information concise, accurate, and organized.

---

# Memory Files

## .agents/agent_md/project-learn.md

Store project-wide knowledge including:

- Project architecture
- Folder structure
- Tech stack
- Design patterns
- State management
- Routing
- Authentication flow
- API conventions
- Database schema overview
- Naming conventions
- Build process
- Deployment process
- CI/CD notes
- Environment variables
- Shared utilities
- Business rules
- Domain knowledge
- Performance considerations
- Security practices
- Common pitfalls
- Frequently modified files
- Dependencies between modules
- Third-party integrations
- Coding standards discovered from the codebase

Update this whenever new project knowledge is learned.

---

## .agents/agent_md/user-learn.md

Continuously learn how I work.

Examples include:

### Coding Preferences

- Naming conventions
- Preferred code style
- Preferred folder structure
- Error handling style
- Logging preferences
- Documentation style
- Testing preferences
- Refactoring preferences
- Commenting preferences

### Workflow Preferences

Learn things like:

- I prefer minimal changes.
- I prefer readable code over clever code.
- I prefer keeping existing architecture.
- I prefer backward compatibility.
- I avoid unnecessary dependencies.
- I prefer reusable utilities.
- I prefer functional programming where appropriate.

### Communication Preferences

Learn things like:

- I prefer concise explanations.
- I want implementation before explanation.
- I prefer complete working code.
- I don't like placeholders.
- I prefer production-ready solutions.

Only store preferences that have been observed multiple times or explicitly stated.

Do not store temporary task information.

---

## Task Knowledge Files

When completing a significant task that contains valuable reusable knowledge, create or update an appropriate file inside `.agents/agent_md/`.

Examples:

```
.agents/agent_md/
│
├── README.md
├── index.md
│
├── project/
│   ├── architecture.md
│   ├── tech-stack.md
│   ├── folder-structure.md
│   ├── coding-conventions.md
│   ├── business-rules.md
│   ├── glossary.md
│   └── dependencies.md
│
├── user/
│   ├── coding-style.md
│   ├── workflow.md
│   ├── preferences.md
│   └── communication.md
│
├── domains/
│   ├── auth.md
│   ├── cart.md
│   ├── checkout.md
│   ├── search.md
│   ├── payments.md
│   ├── seo.md
│   ├── analytics.md
│   ├── rag.md
│   └── ai.md
│
├── patterns/
│   ├── react.md
│   ├── node.md
│   ├── api.md
│   ├── graphql.md
│   ├── mongodb.md
│   └── testing.md
│
├── decisions/
│   ├── ADR-001-routing.md
│   ├── ADR-002-cache.md
│   └── ADR-003-auth.md
│
├── debugging/
│   ├── known-bugs.md
│   ├── common-errors.md
│   ├── production.md
│   └── performance.md
│
└── sessions/
    ├── 2026-07-26.md
    └── 2026-07-27.md

```

Store reusable knowledge such as:

- Architecture decisions
- Important APIs
- Module relationships
- Data flow
- Known issues
- Debugging tips
- Constraints
- Best practices
- Implementation notes
- Edge cases

These files should become documentation for future Agent sessions.

---

# Learning Rules

Whenever solving a problem ask:

"Will this help future tasks?"

If yes:

Update the appropriate `.agents/agent_md` file.

If no:

Do not store it.

Only keep knowledge that has long-term value.

---

# Before Every Task

Before making any changes:

1. Read relevant `.agents/agent_md` files.
2. Understand existing architecture.
3. Reuse existing patterns.
4. Avoid introducing inconsistent solutions.
5. Follow existing conventions.
6. Don't Read all the files fromm `.agents/agent_md` but only relevant.

If the required knowledge is missing:

- Inspect the codebase.
- Learn it.
- Update `.agents/agent_md`.
- Continue with the task.

---

# During Implementation

Whenever you discover:

- hidden architecture
- undocumented conventions
- reusable utilities
- common helper functions
- recurring patterns
- important business logic

record them inside the appropriate `.agents/agent_md` file.

---

# After Completing Every Task

Before finishing:

Review whether you learned:

- new project knowledge
- new coding conventions
- new architecture details
- new user preferences
- reusable debugging information
- reusable implementation patterns

If yes:

Update `.agents/agent_md`.

---

# Memory Quality

Never write:

- Temporary TODOs
- One-time fixes
- Issue-specific notes
- Personal reminders
- Random observations

Always write:

- Stable knowledge
- Reusable knowledge
- Architecture
- Patterns
- Conventions
- Long-term documentation

---

# Updating Existing Knowledge

Do not append duplicate information.

Instead:

- Merge similar knowledge.
- Improve clarity.
- Remove outdated information.
- Keep files organized.

Treat `.agents/agent_md` as living documentation.

---

# Decision Priority

Always make decisions in this order:

1. User instructions
2. `.agents/agent_md` knowledge
3. Existing project conventions
4. Codebase patterns
5. Industry best practices

Never violate a higher-priority rule.

---

# Goal

Continuously make the project easier to understand.

Every completed task should leave behind better documentation and better project memory than before.
