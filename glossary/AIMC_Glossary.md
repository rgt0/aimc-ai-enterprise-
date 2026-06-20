# AIMC Glossary – Enterprise AI Terminology

This glossary defines key AI-related terms as used in the AIMC (AI Mindset & Competence) context.

The focus is on enterprise meaning, not marketing definitions.

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
