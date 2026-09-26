# 📦 Product Requirements (PRD & Stories)

## Overview & Objectives
**Project:** Automated Permit Eligibility Checker (Public Services)
**Problem:** Citizens struggle with confusing municipal permit criteria, leading to incomplete applications, high rejection rates, and staff overload. Current portals are static and lack personalized checks.
**Objective:** Build a Conversational AI Assistant that automates eligibility checks, streamlines the application process, reduces public service staff workload, and drastically improves citizen experience.

## Scope
- **In Scope:** 
  - Conversational AI agent for data collection.
  - Rule-based reasoning engine to evaluate eligibility against criteria.
  - Actionable feedback generation for missing elements.
  - Simple User Interface (UI).
  - Integration with structured criteria (JSON/CSV) and municipal guidelines.
- **Out of Scope:** 
  - Handling real PII (Personally Identifiable Information). Only synthetic/anonymized data will be used.
  - Actual submission of the permit to government backends (this is an eligibility checker).

## Success Metrics
- **Accuracy:** 80%+ assessment accuracy.
- **User Satisfaction:** High satisfaction in demo scenarios.

## User Stories
- **US-01:** As a citizen, I want to chat with an assistant about my permit needs so that I can figure out exactly what documents I need to apply.
- **US-02:** As a citizen, I want the assistant to tell me if I am missing any requirements *before* I submit my application, so that I don't get rejected.
- **US-03:** As a public service worker, I want the AI to pre-screen applicants so that I spend less time doing manual, error-prone verification.

---
## 🔗 Navigation & Context
- **Up:** [[Index]]
- **State:** [[Agent_Handoff]]
- **Implemented via:** [[System_Design]] & [[ML_Design]]
- **Tracked in:** [[Task_Tracker]]
