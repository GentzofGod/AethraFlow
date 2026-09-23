# AethraFlow

<p align="center">
  <strong>The AI-Native Agile Productivity & Project Management Workspace</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Release-v1.0.0--beta-3B82F6?style=for-the-badge" alt="Release Version" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Gemini AI" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Platform-Windows%20|%20Android%20|%20macOS-8B5CF6?style=for-the-badge" alt="Platforms" />
</p>

---

##  Overview

**AethraFlow** is an intelligent, cross-platform productivity and sprint execution workspace designed to eliminate "blank-canvas paralysis" and the goal-to-execution gap. 

Traditional project management tools act as passive databases—requiring you to manually design tickets, guess task durations, and organize complex work structures from scratch. AethraFlow bridges this divide by turning natural language project intent into structured, multi-tier Work Breakdown Structures with estimated time allocations, real-time focus tracking, and an ambient in-app AI Copilot.

---

##  Key Features

###  1. Intelligent AI Goal Decomposition
- **Natural Language to Milestones:** Describe your project deliverable, target timeframe, and frequency. AethraFlow leverages **Google Gemini 2.5 Flash** with schema-enforced structured outputs to automatically engineer comprehensive milestones and granular subtasks.
- **Calibrated Duration Estimates:** Receive realistic time estimates for each step to streamline sprint planning and prevent cognitive overload.
- **Granular Regeneration:** Dynamically tweak, refine, or regenerate individual milestones without losing existing project state.

###  2. Contextual In-App Agile Copilot
- **Real-Time Triage:** Ask questions like *"Summarize sprint status"*, *"What tasks are urgent?"*, or request step-by-step problem breakdown.
- **Deep Workspace Context:** Copilot operates with awareness of active timers, overdue deliverables, subtask completion rates, and priority flags.
- **Automated Actions:** Directly triage overdue tickets to urgent status or scaffold new deliverables from within chat.

###  3. Execution Engine & Focus Tracking
- **Interactive Focus Timers:** Integrated Pomodoro and sprint timers that log actual focus minutes directly against deliverables.
- **Multi-Level Hierarchy:** Organize work up to two levels deep (Parent Goals ➔ Core Subtasks ➔ Child Action Items).
- **Interactive Next-Up Panel:** Prioritized view of immediate next action items across all projects filtered by cadence (Daily, Weekly, Sprint).

###  4. Workflow & Native Integrations
- **Device Calendar Sync:** Seamless two-way synchronization with native OS calendars (Google Calendar, Outlook, Apple Calendar) via standard event formats.
- **Executive Reporting & Export:** Instant generation of executive sprint summaries, formatted markdown reports, and publication-ready PDF exports.
- **Offline & Fallback Support:** Full local guest mode with encrypted persistence and intelligent mock generation when offline.

---

##  Download & Releases

Pre-compiled, production-ready binaries are hosted directly under the **Releases** section:

 **[Download the Latest AethraFlow Release](https://github.com/GentzofGod/AethraFlow/releases)**

| Platform | Format | Status |
| :--- | :--- | :--- |
| **Windows** | `.exe` |  Available |
| **Android** | `.apk` |  Available |


---

##  Built With

- **Framework:** [Flutter](https://flutter.dev) 
- **AI Engine:** [Google Generative AI](https://ai.google.dev/) (Gemini 2.5 Flash)
- **State Management:** [Riverpod](https://riverpod.dev) with code generation
- **Backend & Cloud Persistence:** [Supabase](https://supabase.com) (PostgreSQL, Auth, Realtime)
- **Visualization:** [FL Chart](https://github.com/imaNNeo/fl_chart)
- **Security & Encryption:** AES-256 chat and preference encryption

---

##  Privacy & Security

- **Local Guest Mode:** Full offline functionality without requiring an account.
- **Encrypted Workspace:** Sensitive configuration, API keys, and notes are encrypted at rest.
- **Zero Telemetry:** Your personal tasks and planning notes remain strictly yours.

---

##  Feedback & Support

Found an issue, have an improvement idea, or want to suggest a feature?
- Open an issue in the **[Issues Tab](https://github.com/GentzofGod/AethraFlow/issues)**.
- Follow new feature drops and changelogs on the **[Releases Page](https://github.com/GentzofGod/AethraFlow/releases)**.

---

<p align="center">
  <sub>© 2026 AethraFlow. All rights reserved.</sub>
</p>
