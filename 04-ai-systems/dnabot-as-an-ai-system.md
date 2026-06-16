1. What DNABOT Is (System View)

AI access layer
governed execution
non‑binding output
no memory, no learning

2. What DNABOT Is Not

not a knowledge base
not a DT expert
not a decision maker
not a system of record

3. How DNABOT Processes Input

user input → policy checks
model execution
response generation
no persistence

(itt lehet diagram / ASCII)
4. Why DNABOT Has Restrictions

data protection classes
secret classification
personal data handling
➡️ governance-driven design, nem „feature gap”

5. How Humans Are Expected to Work With DNABOT

DNABOT proposes
human validates
organization remains accountable

6. Typical Failure Modes (Very AIMC!)

wrong assumptions
overtrust
context gaps
outdated knowledge
-------------------
# DNABOT as an AI System

This document describes DNABOT **not as a chatbot**, but as an **enterprise AI system**.
It is written in a *user‑guide style*, **not to teach UI usage**, but to explain:

- how the system behaves
- why it has strict boundaries
- where responsibility lies
- how humans are expected to work with it

This aligns with the AIMC principle:  
**AI systems must be understood as systems, not as smart tools.**

---

## 1. What DNABOT Is (System View)

DNABOT is an **enterprise AI access layer** operated within Deutsche Telekom.

From a system perspective, DNABOT is:

- a governed interface to Large Language Models
- hosted inside DT data centers
- restricted to professional, internal use
- designed to prevent uncontrolled data exposure
- explicitly non‑binding in its outputs

DNABOT enables **safe interaction with AI**, not autonomous decision-making.

---

## 2. What DNABOT Is Not

To avoid misinterpretation, DNABOT is **not**:

- a knowledge base
- a DT expert
- a system of record
- a decision-making authority
- a learning or memory-retaining system

DNABOT does **not**:
- remember past conversations
- retain user input after session end
- update or train models based on user data
- guarantee correctness or completeness

Any perception of “understanding” is a **generated illusion**, not system knowledge.

---

## 3. How DNABOT Processes Input

At a high level, DNABOT operates as follows:
Human Input
↓
Policy & Governance Checks
↓
Model Execution (LLAMA / Mistral)
↓
Response Generation
↓
Human Validation

Key characteristics:

- input is evaluated against protection and governance rules
- no persistent storage of conversations
- no long-term context
- output is generated text, not verified fact

DNABOT processes **text fragments**, not organizational meaning.

---

## 4. Why DNABOT Has Restrictions

DNABOT’s limitations are **intentional design choices**, not feature gaps.

Key drivers:

- data protection classifications
- secret protection constraints
- personal data regulations
- internal governance requirements
- legal accountability boundaries

These restrictions reflect a core AIMC insight:

> **AI complexity does not disappear — it moves into governance and responsibility layers.**

DNABOT demonstrates how enterprise AI is constrained by reality.

---

## 5. How Humans Are Expected to Work With DNABOT

DNABOT follows a clear responsibility model:

- the AI generates **proposals**
- humans validate **meaning and correctness**
- the organization remains **fully accountable**

Expected human behavior:

- critically evaluate every response
- verify against authoritative sources
- treat outputs as suggestions, not answers
- apply domain expertise and judgment

DNABOT supports thinking — it does not replace it.

---

## 6. Typical Failure Modes

Understanding failure modes is essential to responsible usage.

Common patterns:

- over‑trusting fluent responses
- assuming hidden knowledge or memory
- ignoring missing or wrong context
- expecting up‑to‑date information
- treating output as authoritative

These failures are **systemic**, not user mistakes.

They highlight why **human‑in‑the‑loop** is mandatory.

---

## 7. DNABOT in the AIMC Context

Within the AIMC framework, DNABOT serves as:

- a concrete example of an enterprise AI system
- a reference implementation for governed AI access
- a teaching tool for system-level AI thinking

DNABOT validates a recurring AIMC principle:

> **AI does not carry responsibility.  
> People and organizations do.**

---

## 8. Key Takeaway

DNABOT should not be evaluated by:
- speed
- creativity
- or convenience

It should be evaluated by:
- governance alignment
- clarity of responsibility
- and system transparency

DNABOT is not “limited AI”.  
It is **realistic enterprise AI**.

---

┌─────────────────────────┐
                         │         Human            │
                         │  (Employee / Operator)  │
                         └─────────────┬───────────┘
                                       │
                                       │  Professional Input
                                       ▼
┌────────────────────────────────────────────────────────────┐
│                         DNABOT                              │
│                  (AI Access Layer)                          │
│                                                            │
│  ┌──────────────────────────────────────────────────────┐  │
│  │ Governance & Policy Enforcement                        │  │
│  │ - Protection Class checks                              │  │
│  │ - Secret classification limits                         │  │
│  │ - Personal data restrictions                           │  │
│  └──────────────────────────────────────────────────────┘  │
│                          │                                  │
│                          ▼                                  │
│  ┌──────────────────────────────────────────────────────┐  │
│  │ Model Execution                                       │  │
│  │ - Open-source LLMs (LLAMA / Mistral)                   │  │
│  │ - No memory, no learning                               │  │
│  │ - No organizational knowledge                          │  │
│  └──────────────────────────────────────────────────────┘  │
└───────────────────────────┬────────────────────────────────┘
                            │
                            │ Generated Proposal
                            ▼
                 ┌─────────────────────────┐
                 │        Output            │
                 │  (Non-binding Response) │
                 └─────────────┬───────────┘
                               │
                               │ Critical Review & Validation
                               ▼
                 ┌─────────────────────────┐
                 │        Human             │
                 │  Meaning & Responsibility│
                 └─────────────────────────┘

DNABOT does not produce decisions.
It produces proposals.

Meaning, correctness, and responsibility
always remain with humans and the organization.

© AIMC – AI Mindset & Competence  
This document contains no operational instructions and no confidential information.
