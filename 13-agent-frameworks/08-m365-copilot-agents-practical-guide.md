# Microsoft 365 Copilot Agents – Practical Guide

## Purpose

Provide a practical introduction to creating, governing and using AI agents in the Microsoft 365 ecosystem.

This guide focuses on:

- Agent Builder
- Copilot Studio
- Enterprise governance
- Knowledge discovery scenarios

It does not focus on coding.

---

# 1. Agent Creation Options

Microsoft currently provides multiple approaches for building agents.

| Option | Target Audience | Complexity |
|----------|----------|----------|
| Agent Builder | Business users | Low |
| Copilot Studio | Makers / Power Users | Medium |
| Microsoft 365 Agents SDK | Developers | High |

---

# 2. Decision Guide

## Use Agent Builder when

- Personal productivity
- Small team use
- Existing Microsoft 365 content
- No-code requirements

Examples:

```text
Meeting Summary Assistant

Documentation Assistant

Project Status Assistant

Architecture Knowledge Assistant
```

---

## Use Copilot Studio when

- Department-wide deployment
- Enterprise workflows
- Complex orchestration
- External system integration
- Governance requirements

Examples:

```text
Knowledge Discovery Assistant

Release Management Assistant

Architecture Repository Assistant

Service Desk Assistant
```

---

## Use Microsoft 365 Agents SDK when

- Custom AI architecture is required
- Advanced integrations are needed
- Multi-channel deployment is required
- Full software engineering lifecycle is expected

Examples:

```text
Enterprise Architecture Agents

Legacy Modernization Agents

Agent Orchestration Platforms
```

---

# 3. Agent Builder – Quick Start

## Step 1

Open:

```text
Microsoft 365 Copilot
```

Select:

```text
Create Agent
```

or

```text
New Agent
```

depending on the tenant experience.

---

## Step 2

Describe the agent in natural language.

Example:

```text
Create an architecture discovery assistant.

The assistant should:

- analyze architecture notes
- identify applications
- identify dependencies
- classify findings as fact, observation,
  hypothesis or open question
- propose updates to a canonical dictionary
```

Agent Builder automatically generates:

- Name
- Description
- Instructions
- Knowledge Sources
- Suggested Prompts

---

## Step 3

Add knowledge sources.

Examples:

```text
SharePoint Libraries

Word Documents

PDF Documents

Architecture Repositories

Teams Files
```

---

## Step 4

Test the agent.

Example questions:

```text
Which applications use BL733?

Summarize the EBON architecture.

List open architecture questions.

What evidence exists for BST processing?
```

---

# 4. Copilot Studio – Enterprise Pattern

Use Copilot Studio when agent behavior becomes process-oriented rather than purely conversational.

Typical building blocks:

```text
Knowledge

Tools

Actions

Workflows

Connectors
```

Example:

```text
XINFO Discovery Agent

Input:
    XINFO Exports

Actions:
    Extract Applications
    Extract Dependencies
    Build Inventory

Output:
    Evidence Repository Updates
```

---

# 5. Agent Design Pattern for Knowledge Repositories

Recommended architecture:

```text
Discovery Agent
        ↓
Evidence Agent
        ↓
Dictionary Agent
        ↓
Architecture Agent
        ↓
Knowledge Repository
```

Each agent should have exactly one responsibility.

---

# 6. Governance

Enterprise agents should distinguish:

| Classification | Meaning |
|----------------|---------|
| FACT | Verified |
| OBSERVATION | Directly observed |
| HYPOTHESIS | Interpretation |
| OPEN QUESTION | Unknown or unresolved |

This prevents knowledge pollution and unsupported conclusions.

---

# 7. AIMC Agent Examples

## Discovery Agent

Purpose:

```text
Transform artefacts into observations.
```

Inputs:

```text
XINFO
JCL
COBOL
DB2 Metadata
```

Outputs:

```text
Observations
```

---

## Evidence Agent

Purpose:

```text
Transform observations into evidence.
```

Inputs:

```text
Observations
```

Outputs:

```text
Evidence Entries
```

---

## Dictionary Agent

Purpose:

```text
Build and maintain canonical terminology.
```

Inputs:

```text
Evidence
```

Outputs:

```text
Canonical Dictionary
```

---

## Architecture Agent

Purpose:

```text
Transform evidence and dictionary
entries into architecture views.
```

Inputs:

```text
Evidence Repository

Canonical Dictionary
```

Outputs:

```text
Architecture Models
```

---

## Consistency Agent

Purpose:

```text
Validate knowledge quality.
```

Checks:

```text
FACT

OBSERVATION

HYPOTHESIS

OPEN QUESTION
```

---

# 8. Enterprise Knowledge Pipeline

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

# 9. Recommended AIMC Learning Path

```text
1. Agent Builder
        ↓
2. Copilot Studio
        ↓
3. Knowledge Discovery Agents
        ↓
4. Agent Orchestration
        ↓
5. Microsoft 365 Agents SDK
```

---

# Key Principle

Agents do not own knowledge.

Agents generate proposals.

Humans remain responsible for:

- validation
- interpretation
- governance
- approval
- accountability

Enterprise knowledge remains a human responsibility.
