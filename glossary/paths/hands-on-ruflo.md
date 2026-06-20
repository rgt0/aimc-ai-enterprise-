# AIMC Hands‑On Guide – Ruflo from Zero to Swarm

This hands‑on guide introduces Ruflo step by step.
The goal is not to "use a tool", but to understand how an agentic AI system
actually operates in practice.

You will not write Ruflo code.
You will observe how a system behaves.

---

## Prerequisites

- Node.js installed (LTS)
- Terminal / PowerShell
- No prior Ruflo knowledge required

---

## Phase 0 – Mental Reset

Before starting, align expectations:

- Ruflo is not a chatbot
- Ruflo is not a framework you program against
- Ruflo is a **runtime system** that orchestrates agents

You will mostly run commands and observe behavior.

---

## Phase 1 – CLI & Runtime Basics

### Step 1.1 – What is actually executed?

Open a terminal and run:

```bash
npx --version
If this works, your environment is ready.
Key insight:
npx runs software without installing it permanently.

Step 1.2 – Run Ruflo for the first time
Shellnpx ruflo@latest --helpShow more lines
You did not install Ruflo.
You executed it.
Key insight:
Ruflo is a runtime, not a dependency.

Phase 2 – Initialize Ruflo in a Workspace
Step 2.1 – Create a demo folder
Shellmkdir ruflo-democd ruflo-demoShow more lines

Step 2.2 – Initialize Ruflo
Shellnpx ruflo@latest initShow more lines
This creates configuration folders.
Expected result:
Plain Text.claude/.claude-flow/CLAUDE.mdShow more lines
Key insight:
Ruflo integrates by configuration and hooks, not code.

Phase 3 – What is a Hook? (Critical)
You did NOT start any swarm yet.
Hooks work like this:
Plain TextUser action → Hook → Router → SwarmShow more lines
Ruflo hooks are triggered automatically
when meaningful work is detected.
You do not call the swarm directly.

Phase 4 – First Agentic Task
Step 4.1 – Run a simple task
Shellnpx ruflo run \  --task "Explain what this project folder is for"``Show more lines
Observe:

You gave a goal
Ruflo decided how to approach it

Key insight:
This is Agentic AI (goal → steps → execution).

Phase 5 – Making Agents Visible
Now we move from single execution to multi‑agent thinking.
Step 5.1 – Run a decomposition task
Shellnpx ruflo run \  --task "Analyze this repository and propose improvements"Show more lines
Internally Ruflo will:

decompose the task
spawn specialized agents
coordinate their output

You did not define agents.
The system did.
Key insight:
Multi‑agent systems often already exist implicitly.

Phase 6 – Swarm Behavior Emerges
Step 6.1 – Trigger a complex task
Shellnpx ruflo run \  --task "Refactor this COBOL program, generate tests, and validate logic"  --input program.cblShow more lines
What happens:

Analyzer agent understands COBOL
Refactor agent proposes changes
Test agent generates cases
Validator agent checks consistency

These agents may loop and correct each other.
Key insight:
This is swarm behavior, not a linear pipeline.

Phase 7 – Observe Non‑Determinism
Run the same command again:
Shellnpx ruflo run \  --task "Refactor this COBOL program, generate tests, and validate logic"  --input program.cblShow more lines
Compare results.
They may differ.
Key insight:
AI systems are not deterministic pipelines.

Phase 8 – Memory & Learning
Ruflo stores successful patterns.
Step 8.1 – Ask a follow‑up
Shellnpx ruflo run \  --task "Apply the same refactoring approach to a similar COBOL program"Show more lines
Key insight:
The system recalls prior behavior, not documents.
This is RAG + memory.

Phase 9 – Failure Awareness (AIMC Core)
At this point, ask:

Did the analyzer misunderstand logic?
Did refactoring introduce risk?
Did agents disagree?

These are system failures, not "AI mistakes".
Map them to:

Context issues
Coordination issues
Validation gaps


Final Insight
You did not:

write agent code
configure swarms
tune models

Yet you observed:

Agent behavior
Agentic execution
Multi‑agent coordination
Swarm emergence


One‑Sentence Summary
Ruflo is not something you use — it is something you observe to understand how AI systems really behave.
