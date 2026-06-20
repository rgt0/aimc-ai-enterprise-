# AIMC Glossary – Enterprise AI Terminology (v2)

This glossary defines key AI-related terms as used in the AIMC (AI Mindset & Competence) context.

The focus is on enterprise meaning, not marketing definitions.

| Term | Category | Short definition | Enterprise interpretation | AIMC perspective | Common misunderstanding | Failure Mode | Control Mechanism | Link |
|------|----------|------------------|--------------------------|------------------|--------------------------|--------------|-------------------|------|
| Artificial Intelligence (AI) | Core Concept | System component supporting decisions under uncertainty | Capability embedded in systems and processes | Must be understood as part of a governed system | AI is a chatbot | Misplaced expectations | System-level education and governance | ../00-orientation/ |
| Large Language Model (LLM) | Core Concept | Probabilistic language model generating text | Replaceable component inside an AI system | Reasons in language, not reality | Understands the business | Hallucination / false reasoning | Context control and validation | ../01-ai-fundamentals/ |
| AI System | Core Concept | Governed system combining models, data, logic and humans | Impact emerges at system level | Risk is system-level, not model-level | The model is the AI | Integration failure | End-to-end system design and governance | ../04-ai-systems/ |
| Retrieval Augmented Generation (RAG) | Core Concept | Retrieval + generation technique | Enables use of enterprise knowledge without retraining | Shifts risk to knowledge quality | Guarantees correctness | Retrieval mismatch | Improve chunking, indexing, and ranking | ../05-knowledge-and-context/ |
| Context | Core Concept | Information provided to an AI for a task | Determines behavior more than the model | Must be controlled by humans | More context is always better | Context overload / noise | Context curation and filtering | ../05-knowledge-and-context/ |
| Document | Knowledge Model | Human-readable information container | Not directly understood by AI | Split into fragments (chunks) | AI reads documents | Misleading structure | Structured document design | ../05-knowledge-and-context/ |
| Chunk | Knowledge Model | Fragment of a document used in RAG | Atomic knowledge unit | Quality > document size | Just a technical detail | Poor chunk quality | Chunking strategy optimization | ../05-knowledge-and-context/ |
| Governance | Governance | Rules defining allowed AI usage | Defines boundaries and accountability | Prevents systemic risk | Blocks innovation | Over/under-restriction | Balanced policy design | ../07-operating-model/ |
| Responsibility | Governance | Accountability for AI-supported outcomes | Always human-owned, never shifts to AI | Humans validate meaning | “The AI made a mistake” | Ownership ambiguity | Clear accountability definition | ../07-operating-model/ |
| Human-in-the-Loop | Governance | Human validation principle | Mandatory in enterprise AI | Removing humans increases risk | Full automation is the goal | Over-automation | Mandatory validation checkpoints | ../07-operating-model/ |
| STRIVE Platform | Platform | Enterprise delivery and execution platform | AI runs within platform constraints | Platform shapes capability | AI runs independently | Platform bottlenecks | Platform-aware architecture | ../03-strive-platform/ |
| AI Operator (AIO) | Platform | Governed AI system for knowledge & ITSM | System, not user or agent | Context reflection engine | Knows everything | Context misalignment | Input context validation | ../04-ai-systems/ |
| AI Engineer (AIE) | Platform | AI dev-support system | Supports but does not replace engineering | Amplifies assumptions | Writes correct code automatically | Incorrect assumptions propagation | Human review and testing | ../04-ai-systems/ |
| Legacy System | Legacy | Long-lived system with accumulated logic | Contains critical business knowledge | High-value AI target | Obsolete | Misinterpretation of logic | Incremental analysis and validation | ../06-legacy-modernization/ |
| COBOL | Legacy | Enterprise programming language | Encodes decades of business rules | AI accelerates understanding | Irrelevant | Semantic misunderstanding | Domain expert validation | ../06-legacy-modernization/cobol-ai-flow.md |
| Swarm Behavior | System Behavior | Multi-step distributed processing | Implicit multi-agent behavior | Must analyze per step | AI is a single entity | Coordination failure | Task decomposition and orchestration control | ../04-ai-systems/swarm-behavior-in-enterprise-ai.md |
| Non-determinism | System Behavior | Output variability | Caused by context and routing | Expected behavior | Should be consistent | Unexpected variation | Prompt and context stabilization | ../02-enterprise-ai-reality/ |
| Context Drift | System Behavior | Changing context across steps | Leads to inconsistency | Must be controlled | Context is stable | Drift between steps | Context pinning and tracking | ../05-knowledge-and-context/ |
| Ruflo | External System | Multi-agent orchestration framework | Demonstrates swarm execution | Makes hidden system behavior visible | Production-ready enterprise tool | Overcomplex orchestration | Controlled experimental usage | ../04-ai-systems/swarm-behavior-in-enterprise-ai.md |
| Category Definitions | General | Definitions of glossary categories | Structures enterprise AI understanding | Enables system thinking | Categories are optional | Misclassification | Clear taxonomy governance | ../glossary/ |
| Category: Core Concept | General | Basic AI concepts | Foundation for AI reasoning | Defines system-level understanding | Only theoretical | Concept confusion | Training and documentation | ../00-orientation/ |
