# Agentic Knowledge Engineering

## Purpose
## What is Agentic Knowledge Engineering?

Enterprise systems contain vast amounts of information, but very little knowledge.

Knowledge is rarely stored directly.

It is distributed across:

- source code
- batch jobs
- schedulers
- databases
- architecture notes
- operational procedures
- historical decisions

Traditional analysis relies on humans manually collecting, interpreting and documenting these artefacts.

This approach is slow, inconsistent and difficult to scale.

Agentic Knowledge Engineering introduces a structured discovery process in which specialized agents contribute to the creation of architecture knowledge.

The objective is not automation for its own sake.

The objective is to create a repeatable path from technical artefacts to system understanding.

---

## From Information to Knowledge

Most enterprise repositories contain information.

Examples:

```text
COBOL programs
JCL
DB2 tables
XINFO exports
Scheduler definitions
```

These artefacts do not directly explain:

```text
How the system works

Why components exist

How processes interact

What business capabilities are implemented

Which architectural patterns are present
```

Knowledge emerges only when information is interpreted within context.

Agentic Knowledge Engineering formalizes this interpretation process.

---

## Why Agents?

Different discovery activities require different forms of reasoning.

Identifying a program is not the same activity as:

- validating a fact
- building a glossary
- deriving an architecture model

Each activity has different objectives, rules and outputs.

Separating these activities into specialized agents prevents uncontrolled assumptions and improves traceability.

---

## Core Principle

Every architectural statement should be traceable back to evidence.

```text
Artefact
    ↓
Observation
    ↓
Evidence
    ↓
Dictionary
    ↓
Architecture
    ↓
Knowledge
```

This creates a transparent chain of reasoning.

At every stage it must be possible to answer:

```text
Why do we believe this?

Which evidence supports it?

What is known?

What is still a hypothesis?
```

---

## Intended Outcome

The goal is not to generate documents.

The goal is to create a living knowledge system that supports:

- onboarding
- architecture discovery
- system understanding
- modernization initiatives
- impact analysis
- enterprise knowledge preservation

Agentic Knowledge Engineering treats understanding as a process rather than a document.
Most enterprise AI discussions focus on generation.

This section focuses on knowledge creation.

Objective:

Transform enterprise artefacts into structured knowledge.

Examples:

- XINFO exports
- JCL
- COBOL source
- DB2 metadata
- Architecture notes

The goal is not content generation.

The goal is understanding.

---

## Core Principle

```text
Raw Artefact
    ↓
Observation
    ↓
Evidence
    ↓
Dictionary
    ↓
Architecture
    ↓
Knowledge
```

---

## Repository Structure

```text
13-agentic-knowledge-engineering/

├── README.md
├── 01-agent-landscape.md
├── 02-discovery-agent.md
├── 03-evidence-agent.md
├── 04-dictionary-agent.md
├── 05-architecture-agent.md
├── 06-consistency-agent.md
└── 07-enterprise-knowledge-pipeline.md
```

---

## Learning Path

Recommended reading order:

```text
1. Agent Landscape
        ↓
2. Discovery Agent
        ↓
3. Evidence Agent
        ↓
4. Dictionary Agent
        ↓
5. Architecture Agent
        ↓
6. Consistency Agent
        ↓
7. Enterprise Knowledge Pipeline
```

---

## Agent Landscape

| Agent | Responsibility |
|---------|----------------|
| Discovery Agent | Extract observations from artefacts |
| Evidence Agent | Convert observations into evidence |
| Dictionary Agent | Build canonical terminology |
| Architecture Agent | Derive architecture views |
| Consistency Agent | Validate confidence levels and classifications |

---

## Knowledge Creation Pipeline

```text
XINFO
JCL
COBOL
DB2

      ↓

Discovery Agent

      ↓

Observations

      ↓

Evidence Agent

      ↓

Evidence Repository

      ↓

Dictionary Agent

      ↓

Canonical Dictionary

      ↓

Architecture Agent

      ↓

Architecture Views

      ↓

Knowledge Repository
```

---

## Human Responsibility

Agents assist.

Humans remain responsible for:

- validation
- approval
- interpretation
- governance

Agents produce proposals.

Humans own the knowledge.
