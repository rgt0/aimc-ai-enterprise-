# AIMC Glossary – Enterprise AI Terminology

This glossary defines key AI-related terms as used in the AIMC (AI Mindset & Competence) context.

The focus is on **enterprise meaning**, not marketing definitions.

---

## 🧠 Glossary

| Term | Category | Short definition | Enterprise interpretation | AIMC perspective | Common misunderstanding | Link |
|------|----------|------------------|--------------------------|------------------|--------------------------|------|
| Artificial Intelligence (AI) | Core Concept | System component supporting decisions under uncertainty | Capability embedded in systems and processes | Must be understood as part of a governed system | AI is a chatbot | ../00-orientation/ |
| Large Language Model (LLM) | Core Concept | Probabilistic language model generating text | Replaceable component inside an AI system | Reasons in language, not reality | Understands the business | ../01-ai-fundamentals/ |
| AI System | Core Concept | Governed system combining models, data, logic and humans | Impact emerges at system level | Risk is system-level, not model-level | The model is the AI | ../04-ai-systems/ |
| Retrieval Augmented Generation (RAG) | Core Concept | Retrieval + generation technique | Enables use of enterprise knowledge without retraining | Shifts risk to knowledge quality | Guarantees correctness | ../05-knowledge-and-context/ |
| Context | Core Concept | Information provided to an AI for a task | Determines behavior more than the model | Must be controlled by humans | More context is always better | ../05-knowledge-and-context/ |

| Document | Knowledge Model | Human-readable information container | Not directly understood by AI | Split into fragments (chunks) | AI reads documents | ../05-knowledge-and-context/ |
| Chunk | Knowledge Model | Fragment of a document used in RAG | Atomic knowledge unit | Quality > document size | Just a technical detail | ../05-knowledge-and-context/ |

| Governance | Governance | Rules defining allowed AI usage | Defines boundaries and accountability | Prevents systemic risk | Blocks innovation | ../07-operating-model/ |
| Responsibility | Governance | Accountability for AI-supported outcomes | Always human-owned, never shifts to AI | Humans validate meaning | “The AI made a mistake” | ../07-operating-model/ |
| Human-in-the-Loop | Governance | Human validation principle | Mandatory in enterprise AI | Removing humans increases risk | Full automation is the goal | ../07-operating-model/ |

| STRIVE Platform | Platform | Enterprise delivery and execution platform | AI runs within platform constraints | Platform shapes capability | AI runs independently | ../03-strive-platform/ |
| AI Operator (AIO) | Platform | Governed AI system for knowledge & ITSM | System, not user or agent | Context reflection engine | Knows everything | ../04-ai-systems/ |
| AI Engineer (AIE) | Platform | AI dev-support system | Supports but does not replace engineering | Amplifies assumptions | Writes correct code automatically | ../04-ai-systems/ |

| Legacy System | Legacy | Long-lived system with accumulated logic | Contains critical business knowledge | High-value AI target | Obsolete | ../06-legacy-modernization/ |
| COBOL | Legacy | Enterprise programming language | Encodes decades of business rules | AI accelerates understanding | Irrelevant | ../06-legacy-modernization/cobol-ai-flow.md |

| Swarm Behavior | System Behavior | Multi-step distributed processing | Implicit multi-agent behavior | Must analyze per step | AI is a single entity | ../04-ai-systems/swarm-behavior-in-enterprise-ai.md |
| Non-determinism | System Behavior | Output variability | Caused by context and routing | Expected behavior | Should be consistent | ../02-enterprise-ai-reality/ |
| Context Drift | System Behavior | Changing context across steps | Leads to inconsistency | Must be controlled | Context is stable | ../05-knowledge-and-context/ |

| Ruflo | External System | Multi-agent orchestration framework | Demonstrates swarm execution | Makes hidden system behavior visible | Production-ready enterprise tool | ../04-ai-systems/swarm-behavior-in-enterprise-ai.md |

---

## 🧠 Category Definitions

- **Core Concept** → alap AI fogalmak  
- **Knowledge Model** → tudás reprezentáció (RAG, chunking)  
- **Governance** → kontroll és felelősség  
- **Platform** → enterprise execution layer  
- **Legacy** → üzleti és historikus rendszerek  
- **System Behavior** → AI működési viselkedése  
- **External System** → referencia implementációk (nem enterprise tool)

---

## 🔗 Cross-Linking Principle

Each term links to a repository section where the concept is explained in context.

The glossary is not a dictionary.  
It is a **navigation layer for enterprise AI understanding**.

---

## ✅ One-Sentence Summary

This glossary defines how AI behaves in enterprise systems — not how it is marketed.
