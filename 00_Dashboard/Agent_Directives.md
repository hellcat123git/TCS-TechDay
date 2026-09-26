# 🧠 Agent Directives

**Purpose:** High-level instructions for any AI agent interacting with this repository to ensure consistency, prevent context loss, and maintain an organized workspace.

## 1. Context Preservation
- **Never lose state:** Before concluding any task or shutting down, you MUST update [[Handoff_State]].
- **Document decisions:** If you make a design or architecture decision, log the *why* in the appropriate file (e.g., [[2_Model_Architecture]]) using Obsidian callouts like `> [!info] Decision`.

## 2. AI/ML specific rules
- **Traceability:** Every model iteration must be logged in the [[3_Experiment_Tracker]]. 
- **Data immutability:** Never modify raw data files. Only generate transformation scripts.
- **Reproducibility:** Ensure that all dependencies (pip, conda) are strictly version-pinned in the [[Tech Stack]] and codebase.

## 3. Obsidian Markdown Standards
- **Use Wikilinks:** Connect related concepts heavily using `[[Link]]`.
- **Use Tags:** Tag experiment logs with `#experiment/success` or `#experiment/failed`.
- **Properties:** Use YAML frontmatter at the top of ML experiment files for metadata (accuracy, loss, epoch count).
