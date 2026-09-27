# Agentic AI Workspace

A hands-on workspace for learning and building agentic AI systems with LangGraph — covering agent fundamentals, debugging agent behavior, and a progressive series of RAG techniques.

## 📚 Modules
| # | Module | What it covers |
|---|--------|-----------------|
| 1 | LangGraph Basics | Core concepts of building agents with LangGraph |
| 3 | Debugging | Debugging and tracing agent behavior |
| 6 | RAGS | Progressive RAG techniques (see below) |

### 6-RAGS breakdown
| Notebook | Technique |
|----------|-----------|
| `1-AgenticRAG.ipynb` | Agentic RAG — agent decides when/how to retrieve |
| `2-CorrectiveRAG.ipynb` | Corrective RAG — self-correcting retrieval when results are weak |
| `4-AdaptiveRAG.ipynb` | Adaptive RAG — routes queries to different retrieval strategies |

## 🛠️ Tech Stack
- **Language:** Python 3.13
- **Framework:** LangGraph (agent orchestration)
- **LLM providers:** LangChain OpenAI, LangChain Groq
- **Tools:** arxiv, wikipedia (agent tool integrations)
- <!-- fill in: vector store used in the RAG notebooks, if any -->

## 🚀 Getting Started

### Prerequisites
- Python 3.13

### Installation
\`\`\`bash
git clone https://github.com/123456-raul/AgenticAiworkspace.git
cd AgenticAiworkspace
pip install -r requirements.txt
\`\`\`

### Environment Variables
Create a `.env` file (excluded via `.gitignore`) with your API keys:
\`\`\`
OPENAI_API_KEY=your-key-here
GROQ_API_KEY=your-key-here
\`\`\`

### Running a Module
Each numbered folder is a self-contained stage. Navigate in and run its scripts/notebooks, e.g.:
\`\`\`bash
cd "6-RAGS"
jupyter notebook 4-AdaptiveRAG.ipynb
\`\`\`

## 📌 Notes
This repo tracks a learning progression — from core LangGraph agent concepts, through debugging agent behavior, to increasingly advanced RAG techniques (Agentic → Corrective → Adaptive).

## 📌 Future Improvements
- Consolidate into a single end-to-end agentic pipeline
- Add module-level READMEs explaining design decisions in each stage
- Add example runs/outputs (screenshots or notebook outputs) to show the agent in action
