# ASKT as an AI System

## Overview

ASKT is an enterprise AI platform that provides access to organizational knowledge, AI capabilities and specialized assistants.

The platform is evolving from a model based on prompts and apps toward a unified Agent model.

---

# Default Experience

## 1/6 Chat

ASKT starts with the default setting of Telekom Knowledge.

Users immediately gain access to approved enterprise knowledge sources without manually selecting repositories or filters.

Conceptually:

User
↓
Chat
↓
Telekom Knowledge
↓
Answer

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

# Position in the ASKT Ecosystem

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

For many users this is likely the primary entry point into ASKT.

---

# Available Capabilities

### Foundation Model

```text
OpenAI GPT-5.4
```

The agent uses a large language model as its reasoning engine.

---

### Web Search

Capability:

```text
Web Search
```

The agent can potentially extend its knowledge beyond internally stored information when appropriate.

---

### Document Extraction

Capability:

```text
Document Extraction Tool
```

Allows information retrieval from uploaded or referenced documents.

---

### Enterprise Knowledge Sources

Visible integrations include:

```text
ReferFromConfluence
```

This indicates integration with corporate knowledge repositories.

---

### OneDrive Integration

Available capabilities:

```text
list_onedrive_files_and_folders

search_onedrive_file
```

The agent can interact with enterprise file storage.

---

### Outlook Integration

Available capabilities:

```text
fetch_email
fetch_emails

fetch_outlook_attachment

fetch_calendar_attachment

fetch_meetings
```

This suggests access to enterprise communication and collaboration information where permissions allow.

---

# AIMC Interpretation

The description presents the agent as:

```text
Knowledge Expert
```

However, from a systems perspective the agent does not "know everything".

A more accurate model is:

```text
User
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

The distinction is important.

Answer quality depends on:

- available knowledge sources
- permissions
- retrieval quality
- connector availability
- context selection
- model reasoning

not solely on the language model.

---

# Enterprise AI Reality

Marketing view:

```text
Ask anything.
Get answers.
```

Enterprise reality:

```text
Question
↓
Permissions
↓
Knowledge Retrieval
↓
Document Selection
↓
Context Construction
↓
Model Reasoning
↓
Answer
```

The agent functions as an orchestration layer across multiple enterprise systems.

---

# Why It Matters

The Telekom Knowledge Agent demonstrates the shift from:

```text
Searching for information
```

to:

```text
Interacting with a knowledge specialist
```

Users no longer need to manually navigate:

- Confluence
- OneDrive
- Outlook
- meeting repositories

The agent attempts to retrieve and combine the relevant information.

---

# Key Insight

The Telekom Knowledge Agent is not a document repository.

It is a knowledge orchestration system.

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

into a single conversational interface.
---

# From Prompts and Apps to Agents

ASKT announcement:

> Prompts and Apps are now Agents.

The platform unifies previously separate concepts:

- Prompts
- Apps
- Assistants

under a single abstraction:

Agent
---

# Prompts and Apps become Agents

## Platform Update

ASKT announcement:

> Prompts and Apps go together as Agents.
>
> You can now use specialized AI assistants, called agents, in our agents library.
> We have already prepared the most popular agents for you and provided them with existing prompts.

---

# What Changed?

Historically, AI functionality appeared in several forms:

- Prompts
- Apps
- Assistants

Each represented a different way of accessing AI capabilities.

ASKT now unifies these concepts under a single enterprise abstraction:

```text
Agent
```

The objective is to simplify discovery and use.

Users no longer need to decide whether they need a prompt, an app or a specialized assistant.

They simply choose an Agent.

---

# Agent Library

ASKT now provides a centralized Agent Library.

The library contains:

- preconfigured agents
- reusable AI capabilities
- specialized assistants
- domain-focused expertise

Users can:

- create their own agents
- reuse existing agents
- share agents across teams
- build upon previously created prompts

---

# What Happens to Existing Prompts?

Existing prompts are not lost.

Instead:

```text
Prompt
        ↓
Agent Knowledge
        ↓
Agent Behavior
```

Frequently used prompts become part of an agent definition.

The prompt evolves from an isolated instruction to a reusable capability.

---

# Mental Model

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
Reasoning
↓
Answer
```

The interaction becomes more structured and reusable.

---

# Why This Matters

Agents allow organizations to package:

- expertise
- workflows
- prompts
- guidance
- information sources

into repeatable AI capabilities.

Instead of teaching every user how to construct prompts,
the organization can provide predefined specialists.

---

# Enterprise Perspective

For enterprise environments, agents provide:

- consistency
- reuse
- governance
- maintainability
- scalability

Agents become reusable building blocks within the enterprise AI ecosystem.

---

# AIMC Interpretation

This change reflects a broader industry trend:

```text
Prompt Engineering
        ↓
Agent Engineering
```

The focus shifts from writing better prompts to designing better AI systems.

An agent is no longer just an instruction.

An agent is a combination of:

```text
Role
+
Knowledge
+
Instructions
+
Context
+
Tools
```

---

# Key Insight

Prompts are individual instructions.

Agents are reusable enterprise capabilities.

The platform is moving from prompting toward managed AI specialization.
---
---

# Access Your Chat History

## Feature Overview

ASKT provides access to previous conversations through chat history.

Platform description:

> View and manage all your previous conversations.
> Easily find and continue past chats or start fresh.

---

# Why Chat History Matters

Enterprise AI usage is rarely limited to a single interaction.

Many activities require:

- multiple sessions
- iterative refinement
- follow-up questions
- ongoing investigations
- project-based work

Chat history provides continuity across these interactions.

---

# Traditional Model

Without chat history:

```text
Question
↓
Answer
↓
Session Ends
```

The context is lost.

The user must manually recreate previous work.

---

# Conversation-Based Model

With chat history:

```text
Conversation
↓
Stored Context
↓
Follow-up Questions
↓
Extended Conversation
```

The interaction becomes a continuous knowledge process.

---

# Benefits

## Continuity

Previous discussions remain available.

Users can continue earlier work instead of restarting.

---

## Knowledge Discovery

Past conversations become searchable knowledge assets.

Users can revisit:

- decisions
- explanations
- generated content
- analysis results

---

## Productivity

Repeated questions do not always require repeated work.

Existing conversations can be reused and extended.

---

# Enterprise Perspective

In enterprise environments, work is rarely completed in a single interaction.

Examples:

- modernization projects
- incident investigations
- architecture reviews
- onboarding processes
- documentation development

Chat history supports longer-running knowledge workflows.

---

# Risks and Limitations

Chat history should not be confused with organizational knowledge.

Conversation history contains:

```text
Personal Context
```

while enterprise repositories contain:

```text
Organizational Knowledge
```

Both serve different purposes.

---

# AIMC Interpretation

Chat history extends the interaction model:

Without history:

```text
User
↓
Question
↓
Answer
```

With history:

```text
User
↓
Conversation
↓
Accumulated Context
↓
Answer
```

The quality of future interactions may improve because prior context can be reused.

---

# Key Insight

Chat history transforms isolated AI interactions into ongoing conversations.

It supports continuity, reflection, and iterative knowledge work.
---

# Announcements

## Staying Informed

ASKT provides a dedicated Announcements area.

Platform description:

> We are continuously improving askT.
> To make sure you don’t miss anything, you can find all updates clearly listed under Announcements.

---

# Why Announcements Matter

Enterprise AI systems evolve continuously.

Changes can include:

- new agents
- new capabilities
- updated workflows
- UI changes
- governance changes
- knowledge source updates

Without a common communication channel, users may continue operating based on outdated assumptions.

---

# Traditional Enterprise Problem

A common enterprise challenge:

```text
Platform Changes
        ↓
Users Are Not Informed
        ↓
Confusion
        ↓
Support Requests
```

Announcements help reduce this gap.

---

# Operational Perspective

Announcements are not merely product news.

They act as:

- change communication
- feature awareness
- governance messaging
- adoption support

In an enterprise AI platform, understanding platform changes is part of effective usage.

---

# Enterprise AI Reality

AI systems are not static.

Changes may affect:

```text
Knowledge Sources

Agents

Search Behavior

Security Controls

Platform Integrations

Reasoning Features
```

Users benefit from visibility into these changes.

---

# AIMC Interpretation

Announcements provide transparency.

Without announcements:

```text
User
↓
Unexpected System Behavior
↓
Confusion
```

With announcements:

```text
Platform Change
↓
Announcement
↓
User Awareness
↓
---

# Personalize askT

## Personal Settings

ASKT allows users to personalize their experience.

Platform description:

> Now you can change the language and the design of askT in the settings.

Users can adapt the platform to their individual preferences without changing the underlying enterprise functionality.

---

# Why Personalization Matters

Enterprise AI platforms serve diverse user groups.

Users may differ in:

- language preference
- regional settings
- accessibility needs
- visual preferences
- working habits

Personalization helps reduce friction and improve adoption.

---

# Areas of Personalization

## Language

Users can choose their preferred language.

Benefits:

- improved comprehension
- reduced cognitive load
- easier onboarding
- broader accessibility

---

## Visual Design

Users can adjust the appearance of the platform.

Examples:

- theme preferences
- visual layout options
- user interface customization

The objective is not functionality change, but user comfort.

---

# Enterprise Perspective

A common misconception is that personalization and governance are conflicting goals.

In reality:

```text
Personalization
        ≠
Loss of Governance
```

Enterprise platforms can provide:

- governed data
- approved knowledge sources
- standardized workflows

while still allowing users to personalize their experience.

---

# Human-Centered AI

One goal of enterprise AI adoption is reducing unnecessary barriers.

Personalization supports:

```text
User
↓
Comfort
↓
Engagement
↓
Adoption
```

This increases the likelihood that AI capabilities become part of daily work.

---

# AIMC Interpretation

Personalization changes the user experience layer, not the system layer.

System view:

```text
Knowledge
↓
Governance
↓
AI Platform
↓
User Interface
```

Personalization primarily affects:

```text
User Interface
```

while governance, permissions, knowledge retrieval, and enterprise controls remain unchanged.

---

# Key Insight

Enterprise AI systems must balance:

- standardization
- governance
- flexibility
- user experience

Personalization improves usability while preserving enterprise control.
# Bye Bye Filters
---

# Bye Bye Filters

## Platform Update

ASKT announcement:

> Agents are essentially specialists for your requests and can use defined data sources.
> You can create them yourself or use existing ones.
> This eliminates the need for time-consuming filtering.

---

# Traditional Knowledge Retrieval

In many enterprise systems, users must find information manually.

Typical workflow:

```text
User
↓
Search
↓
Filter Results
↓
Open Documents
↓
Read Content
↓
Find Answer
```

The responsibility for selecting relevant information lies primarily with the user.

---

# Agent-Based Retrieval

ASKT introduces a different model.

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

The agent performs much of the retrieval work on behalf of the user.

---

# Agents as Specialists

ASKT describes agents as specialists.

This is an important concept.

An agent is not simply a prompt.

An agent combines:

```text
Role
+
Instructions
+
Knowledge Sources
+
Context
+
Reasoning
```

Examples:

- Documentation Agent
- Coding Agent
- Knowledge Agent
- Modernization Agent

Each specializes in a specific domain or task.

---

# Defined Data Sources

Agents may operate on predefined knowledge sources.

Examples:

```text
Enterprise Knowledge
Project Documentation
Technical Repositories
Guidelines
Procedures
```

This allows the agent to focus on information that is relevant for its purpose.

---

# Why Filters Become Less Important

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

The effort of information selection shifts from the user to the agent.

---

# Enterprise Perspective

This does not eliminate complexity.

It relocates complexity.

Old responsibility:

```text
User filters information
```

New responsibility:

```text
Agent selects information
```

This makes:

- knowledge quality
- retrieval quality
- governance
- permissions
- data source management

more important than before.

---

# Governance Consideration

Removing filters does not remove accountability.

Agents may retrieve information automatically, but humans remain responsible for:

- interpretation
- validation
- decisions
- business outcomes

---

# AIMC Interpretation

This represents a shift from:

```text
Search-Centric Systems
```

toward:

```text
Agent-Centric Systems
```

Users interact with specialists rather than directly navigating information repositories.

---

# Key Insight

Old model:

```text
User finds information.
```

New model:

```text
Agent finds information.
Human validates meaning.
```

ASKT announcement:

> Agents are essentially specialists for your requests and can use defined data sources.
> You can create them yourself or use existing ones.
> This eliminates the need for time-consuming filtering.

Traditional model:

User
↓
Search
↓
Filter
↓
Read
↓
Answer

Agent model:

User
↓
Agent
↓
Knowledge Sources
↓
Context
↓
Answer

---

# Agents as Specialists

The ASKT model describes Agents as specialists.

An Agent combines:

- role
- instructions
- knowledge
- tools
- reasoning

into a reusable enterprise capability.

Examples:

- Knowledge Agent
- Documentation Agent
- Coding Agent
- Modernization Agent

---

# Enterprise Perspective

The shift from prompts to agents reflects a broader trend in enterprise AI systems.

Earlier:

Prompt
↓
Answer

Today:

Agent
↓
Knowledge
↓
Tools
↓
Workflow
↓
Answer

---

# AIMC Interpretation

The visible interface appears simple:

Human
↓
ASKT
↓
Answer

Enterprise reality is more complex:

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
LLM
↓
Answer

This distinction is important because answer quality depends not only on the model but also on:

- knowledge quality
- permissions
- retrieval quality
- governance
- context selection

---

# Key Insight

Old model:

User finds information.

New model:

Agent finds information.

Human validates meaning.Prompt
↓
App
↓
Assistant
↓
Agent
`Prompts and Apps are now 'Agents'
We’ve cleaned things up. 
You can now find the specialized AI assistants in our agents library. 
We’ve already prepared many agents for you and converted frequently used prompts into agents.

# Bye Bye Filters: The Shift from Filtering to Agents

## The Announcement

ASKT states:

> Agents are essentially specialists for your requests and can use defined data sources.
> You can create them yourself or use existing ones.
> This eliminates the need for time-consuming filtering.

---

# What Changed?

Traditional knowledge systems typically work like this:

User
↓
Search
↓
Filter
↓
Open Documents
↓
Interpret Results
↓
Answer

The user is responsible for selecting relevant information.

---

# Agent-Based Model

With Agents, the process becomes:

User
↓
Agent
↓
Knowledge Sources
↓
Reasoning
↓
Answer

The agent becomes responsible for:

- selecting sources
- filtering information
- retrieving context
- creating an answer

---

# Why Filters Become Less Important

In traditional enterprise systems:

```text
Knowledge Base
↓
Search
↓
Filter
↓
Manual Review
↓
Result
The burden is on the user.
In an Agent-driven system:
Plain TextKnowledge Base↓Agent↓Relevant Context↓Result`Show more lines
The burden shifts from the user to the AI system.

Agents as Specialists
The announcement describes Agents as specialists.
This is an important mental model.
An Agent is not simply:
Plain TextPromptShow more lines
An Agent combines:
Plain TextRole+Knowledge Sources+Instructions+Tools+Reasoning``Show more lines
Examples:

COBOL Mentor Agent
Enterprise AI Agent
Documentation Agent
Modernization Agent

Each specializes in a particular domain.

Enterprise Perspective
In enterprise environments, users often spend more time finding information than using it.
Traditional workflow:
Plain TextSearchFilterValidateCompareReadUseShow more lines
Agent workflow:
Plain TextAskReviewValidateUseShow more lines
The objective is not to remove human validation.
The objective is to remove unnecessary information retrieval effort.

Governance Consideration
The removal of filters does not remove responsibility.
Agents may select information automatically.
Humans remain responsible for:

interpretation
validation
decisions
business outcomes


AIMC Interpretation
This is not merely a user-experience improvement.
It represents a shift:
Plain TextFilter-Centric Systems        ↓Agent-Centric SystemsShow more lines
The user no longer interacts directly with a collection of documents.
The user interacts with a specialist that knows how to navigate those documents.

Key Insight
Old model:
User finds information.
New model:
Agent finds information.
Human validates meaning.
