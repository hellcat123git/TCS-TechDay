---
tags: [ml, design, dataset]
---
# 🧠 ML Design (Data & Architecture)

**Purpose:** Consolidates Dataset tracking and Model Architecture.

## 📊 Dataset Registry
- **Source:** Synthetic datasets representing applicant profiles, plus Structured JSON/CSV for permit eligibility criteria. Also public municipal guideline documents for RAG (Retrieval-Augmented Generation).
- **Preprocessing:** 
  - Map criteria from JSON/CSV to logical rules suitable for AI prompt conditioning.
  - Anonymize / Synthesize all user input (Strictly NO personal data used).
> [!warning] Biases: Ensure synthetic data covers edge cases and multiple permit types to guarantee robust reasoning.

## 🤖 Model Architecture
- **Type:** Generative AI Agent (LLM) with Tool-Use / RAG.
- **Framework:** LangChain / LlamaIndex / Composio (for tools). 
- **Core Capabilities:** 
  - Natural Language Understanding (NLU) to parse user inputs.
  - Rule-Based Reasoning Engine (combining LLM logic with JSON criteria).
  - Response Generation (Clear, actionable feedback).

---
## 🔗 Navigation & Context
- **Up:** [[Index]]
- **State:** [[Agent_Handoff]]
- **Training Runs logged in:** [[3_Experiment_Tracker]]
- **App Integration:** [[System_Design]]
