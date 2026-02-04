# AI-Powered Interview Question Generator & Evaluator (LangChain + Azure OpenAI)

This repo contains a notebook that implements a **multi-agent** interview system:
- **JD Analyzer** → extracts requirements & rubric
- **Question Generator** → creates role-specific interview questions
- **Answer Evaluator** → scores candidate answers with evidence
- **Hiring Recommender** → synthesizes final recommendation

It uses **LangGraph** to orchestrate the workflow and a checkpointer for session memory.
