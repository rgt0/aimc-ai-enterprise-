# AIMC Glossary – Enterprise AI Terminology (v2.1)

This glossary defines key AI-related terms as used in the AIMC (AI Mindset & Competence) context.

The focus is on enterprise meaning, not marketing definitions.

| Term | Category | Short definition | Enterprise interpretation | Common misunderstanding | Notes (AIMC) | Link |
|------|----------|------------------|--------------------------|--------------------------|--------------|------|
| Artificial Intelligence (AI) | Core Concept | System component supporting decisions under uncertainty | Capability embedded in systems and processes | AI is a chatbot | Risk: unrealistic expectations. Control: system-level education | ../00-orientation/ |
| Large Language Model (LLM) | Core Concept | Probabilistic language model generating text | Replaceable component inside an AI system | Understands the business | Risk: hallucination. Control: validation + context design | ../01-ai-fundamentals/ |
| AI System | Core Concept | Governed system combining models, data, logic and humans | Impact emerges at system level | The model is the AI | Risk: integration failure. Control: end-to-end system design | ../04-ai-systems/ |
| Retrieval Augmented Generation (RAG) | Core Concept | Retrieval + generation technique | Enables use of enterprise knowledge without retraining | Guarantees correctness | Risk: retrieval mismatch. Control: chunking + ranking quality | ../05-knowledge-and-context/ |
| Context | Core Concept | Input information for AI tasks | Determines behavior more than the model | More context is always better | Risk: overload/noise. Control: context curation | ../05-knowledge-and-context/ |
| Document | Knowledge Model | Human-readable information container | Not directly understood by AI | AI reads documents | Risk: misleading structure. Control: structured content design | ../05-knowledge-and-context/ |
| Chunk | Knowledge Model | Fragment used in RAG | Atomic knowledge unit | Just a technical detail | Risk: poor chunking. Control: chunk optimization | ../05-knowledge-and-context/ |
| Governance | Governance | Rules defining allowed AI usage | Defines accountability boundaries | Blocks innovation | Risk: over/under restriction. Control: balanced policy | ../07-operating-model/ |
| Responsibility | Governance | Accountability for AI-supported outcomes | Always human-owned | “AI made a mistake” | Risk: unclear ownership. Control: explicit responsibility | ../07-operating-model/ |
| Human-in-the-Loop | Governance | Human validation layer | Mandatory in enterprise AI | Full automation is goal | Risk: over-automation. Control: validation checkpoints | ../07-operating-model/ |
| STRIVE Platform | Platform | Enterprise execution platform | AI runs within platform constraints | AI is independent | Risk: platform bottleneck. Control: platform-aware design | ../03-strive-platform/ |
| AI Operator (AIO) | Platform | AI system for knowledge & ITSM | System, not user | Knows everything | Risk: context misalignment. Control: input validation | ../04-ai-systems/ |
| AI Engineer (AIE) | Platform | AI dev-support system | Supports but does not replace dev | Writes correct code | Risk: wrong assumptions. Control: human review | ../04-ai-systems/ |
| Legacy System | Legacy | Long-lived business system | Contains critical knowledge | Obsolete | Risk: misinterpretation. Control: incremental analysis | ../06-legacy-modernization/ |
| COBOL | Legacy | Enterprise programming language | Encodes business logic | Irrelevant | Risk: semantic loss. Control: domain validation | ../06-legacy-modernization/cobol-ai-flow.md |
| Swarm Behavior | System Behavior | Distributed multi-step processing | Implicit multi-agent behavior | AI is single entity | Risk: coordination failure. Control: task orchestration | ../04-ai-systems/swarm-behavior-in-enterprise-ai.md |
| Non-determinism | System Behavior | Output variability | Depends on context and routing | Should be consistent | Risk: unpredictability. Control: stabilization strategies | ../02-enterprise-ai-reality/ |
| Context Drift | System Behavior | Changing context across steps | Causes inconsistency | Context is stable | Risk: drift. Control: context tracking/pinning | ../05-knowledge-and-context/ |
| Ruflo | External System | Multi-agent orchestration framework | Demonstrates swarm execution | Enterprise-ready tool | Risk: overcomplexity. Control: conceptual use only | ../04-ai-systems/swarm-behavior-in-enterprise-ai.md |
| Category Definitions | General | Defines glossary categories | Creates structure for understanding | Categories optional | Risk: inconsistency. Control: taxonomy governance | ../glossary/ |
| Cross-Linking Principle | General | Terms link to deeper explanations | Enables navigation across repo | Glossary is standalone | Risk: loss of context. Control: maintain links | ../glossary/ |
| One-Sentence Summary | General | AI must be understood as system behavior | Enterprise AI is system-level | AI is a feature | Risk: oversimplification. Control: system thinking | ../00-orientation/ |
