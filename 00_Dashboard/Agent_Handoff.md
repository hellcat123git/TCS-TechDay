# 🔄 Agent Handoff & Rules

**Purpose:** The single source of truth for project state and AI collaboration rules.

## 📌 Current Status
- **Last Updated By:** Antigravity
- **Current Phase:** Data Synthesis & Schema Definition Completed

## 🎯 Active Objective
- [x] Synthesize initial dataset (applicant profiles).
- [x] Define the JSON schema for permit eligibility criteria.
- [ ] Choose the LLM framework (e.g. LangChain, LlamaIndex, Composio).
- [ ] Build the core GenAI reasoning engine logic in Python.

## 🚧 Where We Left Off
- Created `data/rules_schema.json` defining the eligibility logic for two permit types (Food Truck and Residential Extension).
- Created `data/synthetic_profiles.json` with 4 test cases ranging from perfect applicants to missing documents and rule violations.
- Next step is to actually write the Python script that loads this JSON and feeds it to an LLM for evaluation!

## 🧠 Agent Directives
1. **Never lose state:** Always update this file before ending a turn.
2. **Document decisions:** Log architectural choices in [[System_Design]] or [[ML_Design]].
3. **Reproducibility:** Log all training runs in [[3_Experiment_Tracker]].

---
## 🔗 Navigation & Context
- **Up:** [[Index]]
- **Core Requirements:** [[Product_Requirements]]
- **Active Tasks:** [[Task_Tracker]]
