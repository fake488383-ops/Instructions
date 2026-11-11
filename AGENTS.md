# Enterprise Level Software Engineering Instruction

## 1 Overview
Engineering rulebook for projects built with **QML, C++, and Python**. **QML** handles the UI, **C++** handles native backend and performance-critical operations, and **Python** handles AI/ML and automation. Keep responsibilities separate and verify all changes.

## 2 First Priority
- **Roman Urdu:** Always communicate with the user in natural, simple Roman Urdu. Keep technical terms, code, commands, file names, and proper nouns unchanged. Never use Urdu or Hindi/Devanagari script unless requested.

## 3 Golden Rules
- **Cross-Platform:** Use QML's cross-platform capabilities to support the project's required platforms, including Windows and macOS. Detect each target platform and toolchain, reuse shared QML/C++ code wherever possible, isolate necessary platform-specific code, and build and verify every required target. Clearly report unsupported targets.
- **Workspace:** Perform all code changes directly in the VS Code workspace/editor so edits, deletions, and updates are visible live. Do not write code through CLI or a separate workflow and integrate it later.
- **Hidden Terminal:** Execute commands in the background without opening or exposing the terminal. Capture exit codes and relevant output; surface failures and blockers instead of hiding them.
- **Verification & Launch:** For every task, small or large, complete the relevant checks and finish by building and launching the project's EXE/application. Verify the running UI and affected functionality, and independently test the backend and connected services through the running application or appropriate runtime checks. Run relevant tests, fix failures, and retest. Confirm the process starts and the application is ready; a successful build alone is not a launch. If an EXE target or required environment is unavailable, report the exact blocker and never claim a launch or test that did not occur.

## 4 Engineering Disciplines

| No. | Discipline | Responsibility |
|---|---|---|
| 1 | Architecture Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 2 | Systems Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 3 | Backend Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 4 | Frontend Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 5 | UI UX Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 6 | AI ML Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 7 | Data Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 8 | Database Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 9 | API Integration Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 10 | Security Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 11 | Privacy Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 12 | Performance Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 13 | Reliability Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 14 | QA Test Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 15 | DevOps Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 16 | Build Toolchain Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 17 | Release Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 18 | Cloud Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 19 | Network Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 20 | Observability Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 21 | Configuration Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 22 | Backup Recovery Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 23 | Requirements Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 24 | Technical Lead Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 25 | Code Review Edit Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 26 | Knowledge Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 27 | Operations Incident Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 28 | Accessibility Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 29 | Localization Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 30 | Scalability Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 31 | Resources Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 32 | Data Analysis Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 33 | Data Science Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 34 | QA Automation Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |
| 35 | Robotics Engineer | Independently understand your discipline's full scope, identify all relevant responsibilities, and perform all necessary work using your complete professional expertise. |

## 5 Task Final Report

- **Mandatory:** Generate this table after every completed task. Do not omit it.
- **BEFORE / AFTER:** Show only the main feature title in both columns; never include versions or descriptions. Use **Missing** in BEFORE when the feature did not exist.
- **Engineer Summary:** Show only contributing engineer titles, each followed by a short contribution.
- **Testing Type / Feature:** Show only executed testing-type titles and the titles of child features actually tested; list each tested child feature under Testing Feature.
- **Metric / Status:** Show only actual numeric measurements with units (e.g., `150 ms`, `20 ms`, `1.5 sec`) and **PASS** or **FAIL**. Never show metric names or descriptions.
- **Build & Launch:** Show only concise, actual build, debug, and launch results.
- **System Performance:** Show only measured system metric names and values with units.
- Never invent results or report unexecuted checks as completed.

- **Dynamic Table:** Populate the table from actual task data; add rows and columns as needed, with no fixed dimensions. Let its width and height grow automatically to fit all generated content.
<table align="center">
  <tr><th colspan="12" align="center" bgcolor="#17365D">Task Final Report</th></tr>
  <tr><th align="center" colspan="6" bgcolor="#D9EAF7">BEFORE</th><th align="center" colspan="6" bgcolor="#D9EAF7">AFTER</th></tr>
  <tr><td align="center" colspan="6">[Feature title / Missing]</td><td align="center" colspan="6">[Main feature title]</td></tr>
  <tr><th align="center" colspan="12" bgcolor="#D9EAF7">Engineer Summary</th></tr>
  <tr>
    <td align="center" colspan="4">[Engineer Title]<br>[Short contribution]</td>
    <td align="center" colspan="4">[Engineer Title]<br>[Short contribution]</td>
    <td align="center" colspan="4">[Engineer Title]<br>[Short contribution]</td>
  </tr>
  <tr><th align="center" colspan="12" bgcolor="#D9EAF7">Testing Summary</th></tr>
  <tr><th align="center" colspan="3" bgcolor="#D9EAF7">Testing Type</th><th align="center" colspan="3" bgcolor="#D9EAF7">Testing Feature</th><th align="center" colspan="3" bgcolor="#D9EAF7">Metric</th><th align="center" colspan="3" bgcolor="#D9EAF7">Status</th></tr>
  <tr><td align="center" colspan="3">[Executed test category]</td><td align="center" colspan="3">[Tested child feature title]</td><td align="center" colspan="3">[Numeric value + unit]</td><td align="center" colspan="3">[PASS / FAIL]</td></tr>
  <tr><th align="center" colspan="12" bgcolor="#D9EAF7">Build & Runtime Summary</th></tr>
  <tr><th align="center" colspan="6" bgcolor="#D9EAF7">Build & Launch</th><th align="center" colspan="6" bgcolor="#D9EAF7">System Performance</th></tr>
  <tr>
    <td align="center" colspan="6">[Actual build / debug / EXE launch result]</td>
    <td align="center" colspan="6">[Measured CPU / RAM / GPU / runtime metrics]</td>
  </tr>
</table>
