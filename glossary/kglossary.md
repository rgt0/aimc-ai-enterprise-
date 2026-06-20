# AIMC Knowledge Glossary (kglossary)

This glossary defines key AI-related concepts as used in the AIMC (AI Mindset & Competence) context.

Focus: understanding, not operation.

| Term | Category | Short definition | Enterprise interpretation | Common misunderstanding | Notes (AIMC) | Link |
|------|----------|------------------|--------------------------|--------------------------|--------------|------|
| Artificial Intelligence (AI) | Core Concept | System component supporting decisions under uncertainty | Capability embedded in systems and processes | AI is a chatbot | Risk: unrealistic expectations. Control: system-level education | ../00-orientation/ |
| Large Language Model (LLM) | Core Concept | Probabilistic language model generating text | Replaceable component inside an AI system | Understands the business | Risk: hallucination. Control: validation + context design | ../01-ai-fundamentals/ |
| Command Line Interface (CLI) | Core Concept | Text-based interface for executing commands | Primary interaction surface for runtime systems | CLI reveals system behavior explicitly | CLI is outdated or low-level | ../paths/hands-on-ruflo.md |
| Runtime | Core Concept | Environment where software executes | Determines how and when AI systems actually run | AI behavior depends on runtime, not model | AI runs independently of environment | ../paths/hands-on-ruflo.md |
| npm | Platform | Node package manager | Distribution and dependency layer for tools | Not part of AI logic, but execution | npm is only for developers | ../paths/hands-on-ruflo.md |
| npx | Platform | Execute packages without installation | Enables ephemeral execution of AI systems | Execution without adoption | npx installs software permanently | ../paths/hands-on-ruflo.md |
| Hook | System Behavior | Automatic reaction to an event | Triggers AI behavior without manual invocation | Hooks hide orchestration complexity | Hooks are explicit API calls | ../paths/hands-on-ruflo.md |
| Router | System Behavior | Task decomposition and routing logic | Determines which agents handle which subtask | Routing shapes system behavior | Routing is deterministic | ../04-ai-systems/ |
| Shared Memory | Knowledge Model | Persistent memory across executions | Enables learning and recall across runs | Memory drives system evolution | Memory is just storage | ../05-knowledge-and-context/ |
| Execution Layer | Platform | Layer executing tools and actions | Where AI decisions become real effects | Execution is where risk materializes | Execution is neutral | ../paths/hands-on-ruflo.md |
| Feedback Loop | System Behavior | Iterative refinement cycle | Enables correction and learning | AI improves via loops, not answers | AI learns instantly | ../paths/hands-on-ruflo.md |
| Agent | Core Concept | Goal-driven execution unit | Represents a single step in an AI system | Smart autonomous AI entity | Risk: oversimplification. Control: clear role definition and scope | ../04-ai-systems/ |
| Agentic AI | System Behavior | AI performing multi-step actions | Acts as a workflow engine executing sequences | Just better prompting | Risk: hidden complexity. Control: step visibility and tracing | ../04-ai-systems/ |
| Multi-Agent System | System Behavior | Multiple agents working toward a goal | Represents integrated subsystems or coordinated components | Fully controlled system | Risk: coordination issues. Control: orchestration and role separation | ../04-ai-systems/ |
| AI System | Core Concept | Governed system combining models, data, logic and humans | Impact emerges at system level | The model is the AI | Risk: integration failure. Control: end-to-end design | ../04-ai-systems/ |
| Retrieval Augmented Generation (RAG) | Core Concept | Retrieval + generation technique | Enables enterprise knowledge usage | Guarantee| Agent | Core Concept | Goal-driven execution unit | Represents a single step in an AI system | Smart autonomous AI entity | Risk: oversimplification. Control: clear role definition and scope | ../04-ai-systems/ |
| Agentic AI | System Behavior | AI performing multi-step actions | Acts as a workflow engine executing sequences | Just better prompting | Risk: hidden complexity. Control: step visibility and tracing | ../04-ai-systems/ |
| Multi-Agent System | System Behavior | Multiple agents working toward a goal | Represents integrated subsystems or coordinated components | Fully controlled system | Risk: coordination issues. Control: orchestration and role separation | ../04-ai-systems/ |s correctness | Risk: retrieval mismatch. Control: chunking + ranking | ../05-knowledge-and-context/ |
| Context | Core Concept | Input information for AI tasks | Drives behavior more than the model | More context is always better | Risk: overload/noise. Control: context curation | ../05-knowledge-and-context/ |
| Document | Knowledge Model | Human-readable content | Not directly understood by AI | AI reads documents | Risk: structure mismatch. Control: structured docs | ../05-knowledge-and-context/ |
| Chunk | Knowledge Model | Fragment used in RAG | Atomic knowledge unit | Just a technical detail | Risk: poor chunking. Control: chunk strategy | ../05-knowledge-and-context/ |
| Governance | Governance | Rules defining AI usage | Defines accountability boundaries | Blocks innovation | Risk: over/under-control. Control: balanced governance | ../07-operating-model/ |
| Responsibility | Governance | Accountability for outcomes | Always human-owned | “AI made a mistake” | Risk: unclear ownership. Control: explicit roles | ../07-operating-model/ |
| Human-in-the-Loop | Governance | Human validation | Mandatory in enterprise AI | Full automation is goal | Risk: over-automation. Control: validation checkpoints | ../07-operating-model/ |
