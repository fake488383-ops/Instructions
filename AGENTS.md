# Enterprise Level Software Engineering Instruction

## 1 Overview
Project-aware engineering rulebook. Detect project requirements, architecture, technologies, platforms, tools, and constraints. Follow existing conventions. For Jarvis and applicable native desktop projects, prefer **QML** for UI, **C++** for core logic, and **Python** for AI and automation. Complete relevant implementation, debugging, testing, and verification.

## 2 First Priority
- **Roman Urdu:** Always communicate with the user in natural, simple Roman Urdu. Keep technical terms, code, commands, file names, and proper nouns unchanged. Never use Urdu or Hindi/Devanagari script unless requested.

## 3 Golden Rules
- **Cross-Platform:** Detect target platforms and toolchains from project files. Reuse shared code, isolate platform-specific logic, and verify every required target. Clearly report unsupported targets.
- **Workspace Editing:** Identify the correct workspace and project root before editing. Locate files by project structure and references; edit in place, preserve conventions, and avoid duplicate or unrelated files.
- **Hidden Terminal:** Execute commands in the background without opening or exposing the terminal. Capture exit codes and relevant output; surface failures and blockers instead of hiding them.
- **VS Code:** Use the active workspace, Problems, tasks, debug configurations, and available editor tools. Reload only when required, then confirm extensions and workspace are ready.
- **Existing Architecture:** Inspect project structure, entry points, dependencies, and data flow before changes. Respect folder ownership, naming, build paths, and established patterns; make the smallest compatible change.
- **Missing Files:** Verify the path, naming, case, and references; search the project once. Reuse a valid equivalent or create the file only when architecture requires it. Otherwise report the missing dependency; do not loop.
- **Verification & Launch:** Verify changes at the appropriate levels: static checks, build, tests, and runtime. Before EXE launch, inspect Problems and debug state; verify visible UI, text, controls, and affected backend, voice, and database flows. Fix and retest failures; report checks not performed.

## 5 Engineering Disciplines
Preserve all 35 engineer names, numbers, and responsibilities. Understand the request and acceptance criteria; inspect project structure, files, dependencies, and existing behavior. Detect task scope, components, dependencies, risks, and conventions; analyze text/UI references and change impact before editing. Select only relevant disciplines and divide work by responsibility. Choose the smallest architecture-compatible solution and implement it directly. The Technical Lead coordinates tasks, dependencies, integration, and conflicts. Delegate when subagents are available; otherwise work sequentially. Each selected engineer owns assigned analysis, implementation, testing, and verification. Diagnose errors, recover independently, and retest affected components. Verify static checks, builds, tests, runtime behavior, and regression impact; never claim unperformed checks. Ask only when essential information or authorization is missing. Report actual contributors, changes, results, metrics, and remaining blockers.

- **Concise Updates:** Inspect before editing, merge related rules, and avoid duplication.

| No. | Discipline | Responsibility |
|---|---|---|
| 1 | Architecture Engineer | Structure, folders, boundaries, patterns, and modularity. |
| 2 | Systems Engineer | End-to-end behavior, interfaces, lifecycle, compatibility, and embedded integration. |
| 3 | Backend Engineer | Services, business logic, security controls, and concurrency. |
| 4 | Frontend Engineer | Rendering, state, navigation, responsiveness, and integration. |
| 5 | UI UX Engineer | User flows, interaction, usability, and consistency. |
| 6 | AI ML Engineer | Models, prompts, inference, training, grounding, and safety. |
| 7 | Data Engineer | Data pipelines, transformation, lineage, quality, and governance. |
| 8 | Database Engineer | Schemas, queries, indexing, integrity, and recovery. |
| 9 | API Integration Engineer | API contracts, protocols, validation, retries, and interoperability. |
| 10 | Security Engineer | Threats, access control, secrets, and authorized security tests. |
| 11 | Privacy Engineer | Consent, data minimization, retention, and privacy obligations. |
| 12 | Performance Engineer | Profiling, latency, throughput, CPU/GPU, memory, and benchmarks. |
| 13 | Reliability Engineer | Availability, resilience, fault isolation, and recovery. |
| 14 | QA Test Engineer | Test strategy, functional coverage, defect checks, and acceptance. |
| 15 | DevOps Engineer | CI/CD, environments, infrastructure, and delivery. |
| 16 | Build Toolchain Engineer | Compilers, SDKs, dependencies, and reproducible builds. |
| 17 | Release Engineer | Versioning, signing, validation, rollout, and rollback. |
| 18 | Cloud Engineer | Cloud design, hosting, provisioning, capacity, and cost. |
| 19 | Network Engineer | Topology, routing, DNS, protocols, access, and capacity. |
| 20 | Observability Engineer | Logs, metrics, traces, dashboards, and alerts. |
| 21 | Configuration Engineer | Config schemas, environments, defaults, validation, and secrets. |
| 22 | Backup Recovery Engineer | Backup, retention, restoration, and recovery tests. |
| 23 | Requirements Engineer | User needs, requirements, constraints, and acceptance criteria. |
| 24 | Technical Lead Engineer | Task planning, coordination, dependencies, and conflict resolution. |
| 25 | Code Review Edit Engineer | Correctness, maintainability, reviews, and static analysis. |
| 26 | Knowledge Engineer | Documentation, source accuracy, discoverability, and consistency. |
| 27 | Operations Incident Engineer | Incident triage, diagnosis, restoration, and prevention. |
| 28 | Accessibility Engineer | Semantics, keyboard access, assistive tech, and accessibility tests. |
| 29 | Localization Engineer | Languages, scripts, direction, locale formats, and regional support. |
| 30 | Scalability Engineer | Growth, concurrency, load tests, and capacity limits. |
| 31 | Resources Engineer | Compute, memory, storage, network, licensing, and cost. |
| 32 | Data Analysis Engineer | Analyze logs, usage, metrics, trends, and anomalies. |
| 33 | Data Science Engineer | Statistics, experiments, predictive analytics, and model evaluation. |
| 34 | QA Automation Engineer | Automated test frameworks, UI/API tests, and regression suites. |
| 35 | Robotics Engineer | Robot software, sensors, actuators, control, navigation, and simulation. |

## Task Final Report

- **Rendering:** Generate the report directly in the final AI-agent response as standard GitHub-Flavored Markdown. Use one continuous Markdown table, not separate tables, and do not put table syntax inside a code block or quotation. Do not output HTML, CLI/ASCII, Unicode box-drawing tables, or a separate report file.
- **Exact Layout:** Use the title **Task Final Report** and preserve these three sections in this exact order within the same continuous table: **Before / After**, **Engineer Summary**, then **Testing Summary**. Each section must retain its own heading row and column layout as shown:

  | **Before / After** | | |
  |---|---|---|
  | **Before** | **After** | |
  | [Actual existing feature name, or Missing] | [Actual updated feature name] | |

  | **Engineer Summary** | | |
  |---|---|---|
  | **Engineer** | **Title** | **Contribution** |
  | [Exact engineer name] | [Exact discipline title] | [Very short actual contribution] |

  | **Testing Summary** | | | |
  |---|---|---|---|
  | **Testing Type** | **Testing Feature** | **Metric** | **Status** |
  | [Actual test type] | [Actual tested child feature] | [Measured value with unit, or —] | [Pass/Fail] |

- **Single Continuous Table:** Join all three sections into one Markdown table. Do not create independent tables or replace the three layouts with one generic set of columns. Keep the section heading rows and their respective column headings in the same table; use blank cells where a row has fewer columns.
- **Before/After Rules:** Show actual existing and changed main feature names only. Use **Missing** only when a feature did not exist before. Do not write explanations such as added, improved, or updated in the cells.
- **Engineer Summary Rules:** Include only actual contributing engineers from the 35-engineer **Engineering Disciplines** list. Use each exact listed name and title; never invent names or include non-contributors. Give each a very short contribution.
- **Testing Summary Rules:** Generate Testing Types dynamically from tests actually performed. List actual tested child features first; place execution and system-performance checks (Build, Debug, Build & Run, CPU, Startup Time, Performance, Memory, etc.) at the end. Show relevant measured Metrics as short real-time values with units (e.g., 120 ms, 98%, 35%, 450 MB, 60 FPS); use **—** when no metric applies or is available. Status must show only **Pass** or **Fail**. Generate rows dynamically, avoid fixed lists and duplicates, and never mark unperformed tests as passed.
