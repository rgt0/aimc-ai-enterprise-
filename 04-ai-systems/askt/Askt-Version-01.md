# ASKT as an AI System

## Overview

ASKT is an enterprise AI platform that provides access to organizational knowledge, AI capabilities and specialized assistants.

The platform is evolving from a model based on prompts and apps toward a unified Agent model.

---

# Default Experience

## Telekom Knowledge

ASKT starts with the default setting of Telekom Knowledge.

Users immediately gain access to approved enterprise knowledge sources without manually selecting repositories or filters.

Conceptually:

```text
User
↓
Chat
↓
Telekom Knowledge
↓
Answer
```

The user focuses on the question rather than the location of information.

---

# Telekom Knowledge Agent

## Description

ASKT description:

> Your DT knowledge expert that knows all the ins and outs of your business.
> Ask it anything, it's got the answers you need, when you need them.

Statistics:

```text
393.5K chats started with this agent
```

---

## Position in the ASKT Ecosystem

The Telekom Knowledge Agent appears to be the default enterprise knowledge agent within the ASKT platform.

Conceptually:

```text
Employee
↓
Telekom Knowledge Agent
↓
Enterprise Knowledge Sources
↓
Answer
```

---

## Available Capabilities

### Foundation Model

```text
OpenAI GPT-5.4
```

### Knowledge and Retrieval

```text
Web Search

Document Extraction Tool

ReferFromConfluence
```

### OneDrive Integration

```text
list_onedrive_files_and_folders

search_onedrive_file
```

### Outlook Integration

```text
fetch_email
fetch_emails

fetch_outlook_attachment

fetch_calendar_attachment

fetch_meetings
```

---

## Enterprise Reality

Although the user sees:

```text
Human
↓
Telekom Knowledge Agent
↓
Answer
```

the actual system is closer to:

```text
Human
↓
Telekom Knowledge Agent
↓
Enterprise Connectors
↓
Knowledge Sources
↓
Retrieved Context
↓
GPT Model
↓
Answer
```

Output quality depends on:

- knowledge quality
- permissions
- retrieval quality
- connector availability
- context selection
- reasoning quality

---

# From Prompts and Apps to Agents

ASKT announcement:

> Prompts and Apps are now Agents.

Historically, AI functionality appeared in several forms:

- Prompts
- Apps
- Assistants

ASKT now unifies these concepts under one abstraction:

```text
Agent
```

---

## Agent Library

ASKT provides a centralized Agent Library.

The library contains:

- preconfigured agents
- reusable AI capabilities
- specialized assistants
- domain-focused expertise

Users can:

- create agents
- reuse agents
- share agents
- build on existing prompts

---

## What Happens to Existing Prompts?

Existing prompts are not removed.

Instead:

```text
Prompt
        ↓
Agent
```

Frequently used prompts become part of reusable agent behavior.

---

## Mental Model

Old model:

```text
User
↓
Prompt
↓
Answer
```

New model:

```text
User
↓
Agent
↓
Knowledge
↓
Instructions
↓
Tools
↓
Reasoning
↓
Answer
```

---

# Bye Bye Filters

ASKT announcement:

> Agents are essentially specialists for your requests and can use defined data sources.
> You can create them yourself or use existing ones.
> This eliminates the need for time-consuming filtering.

---

## Traditional Knowledge Retrieval

```text
User
↓
Search
↓
Filter
↓
Open Documents
↓
Read Content
↓
Find Answer
```

Users were responsible for information selection.

---

## Agent-Based Retrieval

```text
User
↓
Agent
↓
Selected Data Sources
↓
Context Retrieval
↓
Answer
```

The agent performs much of the retrieval work.

---

## Agents as Specialists

An Agent combines:

```text
Role
+
Knowledge Sources
+
Instructions
+
Tools
+
Reasoning
```

Examples:

- Knowledge Agent
- Documentation Agent
- Coding Agent
- Modernization Agent

---

## Why Filters Become Less Important

Traditional approach:

```text
Knowledge Base
↓
Search
↓
Filter
↓
Read
↓
Answer
```

Agent approach:

```text
Knowledge Base
↓
Agent
↓
Retrieved Context
↓
Answer
```

The effort shifts from the user to the platform.

---

## Governance Perspective

Removing filters does not remove accountability.

Humans remain responsible for:

- interpretation
- validation
- decisions
- business outcomes

---

# Access Your Chat History

ASKT provides access to previous conversations.

Platform description:

> View and manage all your previous conversations.
> Easily find and continue past chats or start fresh.

---

## Traditional Model

```text
Question
↓
Answer
↓
Session Ends
```

---

## Conversation-Based Model

```text
Conversation
↓
Stored Context
↓
Follow-up Questions
↓
Extended Conversation
```

---

## Benefits

- continuity
- knowledge discovery
- productivity
- reusable conversations

---

## Important Distinction

Conversation history is:

```text
Personal Context
```

not:

```text
Organizational Knowledge
```

---

# Announcements

ASKT provides an Announcements area.

Platform description:

> We are continuously improving askT.
> To make sure you don’t miss anything, you can find all updates clearly listed under Announcements.

---

## Why It Matters

Enterprise AI systems evolve continuously.

Typical changes:

- new agents
- new capabilities
- governance updates
- platform integrations
- retrieval improvements

Announcements improve transparency and adoption.

---

# Personalize askT

Platform description:

> Now you can change the language and the design of askT in the settings.

---

## Areas of Personalization

### Language

Users can select their preferred language.

Benefits:

- easier onboarding
- improved comprehension
- lower cognitive load

### Visual Design

Users can customize interface appearance.

Examples:

- themes
- visual preferences
- layout settings

---

## Enterprise Perspective

```text
Personalization
        ≠
Loss of Governance
```

Enterprise controls remain unchanged while user experience becomes more flexible.

---

# AIMC Interpretation

ASKT should not be viewed as a chatbot.

ASKT is an enterprise AI system.

The visible interaction is:

```text
Human
↓
ASKT
↓
Answer
```

The actual system contains additional layers:

```text
Human
↓
ASKT
↓
Knowledge Layer
↓
Permissions
↓
Retrieval
↓
Enterprise Integrations
↓
LLM
↓
Answer
```

---

# Key Insights

## 1. ASKT is an Enterprise AI Platform

It is more than a chat interface.

---

## 2. Telekom Knowledge is a Knowledge Orchestration System

Its value comes from combining:

```text
Enterprise Knowledge
+
Enterprise Integrations
+
Retrieval
+
Reasoning
```

---

## 3. The Platform is Moving from Prompt Engineering to Agent Engineering

```text
Prompt
↓
App
↓
Assistant
↓
Agent
```

---

## 4. Complexity Has Not Disappeared

It has moved from:

```text
User Filtering
```

to:

```text
Knowledge Retrieval
Permissions
Governance
Agent Configuration
```

---

## 5. Responsibility Remains Human

Agents generate answers.

Humans validate meaning.

Organizations remain accountable.
