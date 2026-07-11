# Copilot Studio for Knowledge Discovery

## Purpose

Copilot Studio enables organizations to build enterprise-grade agents that transform distributed information into structured knowledge.

Unlike simple question-and-answer assistants, knowledge discovery agents help users:

- discover relationships
- identify patterns
- extract evidence
- build understanding
- maintain knowledge repositories

Typical sources include:

- SharePoint
- Microsoft Teams
- Databases
- Enterprise documentation
- Source code repositories
- Architecture repositories
- Operational knowledge bases

---

# Why Copilot Studio?

Knowledge discovery often requires more than document retrieval.

Key challenges:

```text
Information exists
    ≠
Knowledge exists
```

Enterprise information is typically distributed across:

- documents
- source code
- databases
- ticketing systems
- wikis
- SharePoint sites
- email archives

Copilot Studio allows agents to orchestrate discovery across multiple sources.

---

# Knowledge Discovery vs Traditional Search

## Traditional Search

```text
Question
    ↓
Search
    ↓
Document
```

Goal:

```text
Find information.
```

---

## Knowledge Discovery

```text
Question
    ↓
Evidence Collection
    ↓
Pattern Detection
    ↓
Interpretation
    ↓
Knowledge
```

Goal:

```text
Build understanding.
```

---

# Typical Agent Architecture

```text
User
    ↓
Knowledge Discovery Agent
    ↓
Knowledge Sources

    ├─ SharePoint
    ├─ Teams
    ├─ Wiki
    ├─ Source Repository
    ├─ DB Metadata
    └─ Architecture Documentation
```

---

# Discovery-Oriented Agent Design

## Discovery Agent

Purpose:

```text
Extract observations.
```

Examples:

- Applications
- Programs
- Interfaces
- Dependencies
- Data stores

Input:

```text
Raw enterprise artefacts
```

Output:

```text
Observations
```

Example:

```text
BL740 executes BL755.
```

Classification:

```text
OBSERVATION
```

---

## Evidence Agent

Purpose:

```text
Create verifiable evidence.
```

Input:

```text
Observations
```

Output:

```text
Evidence entries
```

Example:

```text
Source:
JCL

Finding:
BL740 executes BL755.

Classification:
FACT
```

---

## Dictionary Agent

Purpose:

```text
Create canonical terminology.
```

Input:

```text
Evidence
```

Output:

```text
Canonical dictionary
```

Example:

```text
BL733B
    ↓
Runtime Configuration Service
```

---

## Architecture Agent

Purpose:

```text
Derive architecture views.
```

Input:

```text
Dictionary
Evidence
```

Output:

```text
Layer Models
System Maps
Application Families
```

Example:

```text
Configuration Layer

Runtime Layer

Processing Layer

Reporting Layer
```

---

# Copilot Studio Components

## Knowledge

Provides information sources.

Examples:

```text
SharePoint

Teams

Enterprise Documentation

Architecture Repository
```

---

## Topics

Define conversational entry points.

Examples:

```text
Discover applications

Explain architecture

Find dependencies

Summarize systems

Describe business processes
```

---

## Actions

Perform structured operations.

Examples:

```text
Search repository

Read metadata

Generate evidence entries

Update dictionary

Create architecture summary
```

---

## Connectors

Allow integration with enterprise systems.

Examples:

```text
SharePoint

Dataverse

SQL

ServiceNow

GitHub

Custom APIs
```

---

# Knowledge Discovery Pattern

## Step 1

Collect artefacts.

Examples:

```text
XINFO exports

JCL

Source code

DB metadata

Process documentation
```

---

## Step 2

Extract observations.

Example:

```text
Application exists.

Program exists.

Dependency exists.
```

---

## Step 3

Build evidence.

Example:

```text
Evidence E-001

Source:
XINFO

Finding:
Application BL740 exists.
```

---

## Step 4

Normalize terminology.

Example:

```text
BL733B
    ↓
Runtime Configuration Service
```

---

## Step 5

Generate architecture models.

Example:

```text
Configuration Layer
      ↓
Processing Layer
      ↓
Reporting Layer
```

---

# Governance Pattern

Knowledge discovery agents should never treat assumptions as facts.

Recommended classifications:

| Classification | Meaning |
|----------------|---------|
| FACT | Verified |
| OBSERVATION | Directly observed |
| HYPOTHESIS | Interpretation |
| OPEN QUESTION | Unresolved |

---

# Human-in-the-Loop

Knowledge discovery is not fully autonomous.

Agents support:

```text
Collection

Correlation

Summarization

Classification
```

Humans remain responsible for:

```text
Validation

Interpretation

Approval

Governance

Accountability
```

---

# AIMC Pattern

Agentic knowledge discovery follows:

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

The objective is not document generation.

The objective is enterprise understanding.
