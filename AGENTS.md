# Enterprise Level Software Engineering Instruction

## 1 Overview
Engineering rulebook for projects built with **QML, C++, and Python**. **QML** handles the UI, **C++** handles native backend and performance-critical operations, and **Python** handles AI/ML and automation. Keep responsibilities separate and verify all changes.

## 2 First Priority
- **Roman Urdu:** Always communicate with the user in natural, simple Roman Urdu. Keep technical terms, code, commands, file names, and proper nouns unchanged. Never use Urdu or Hindi/Devanagari script unless requested.

## 3 Golden Rules
- **Cross-Platform:** Use QML's cross-platform capabilities to support the project's required platforms, including Windows and macOS. Detect each target platform and toolchain, reuse shared QML/C++ code wherever possible, isolate necessary platform-specific code, and build and verify every required target. Clearly report unsupported targets.
- **Workspace:** Make all code changes directly in the VS Code workspace/editor, with live file updates and preview visible as work progresses. Never write code in CLI mode and paste or integrate it afterward.
- **Hidden Terminal:** Execute commands in the background without opening or exposing the terminal. Capture exit codes and relevant output; surface failures and blockers instead of hiding them.
- **Verification & Launch:** For every task, small or large, build and launch the project's EXE/application as a mandatory completion step. Verify the running UI and affected functionality, and independently test the backend and connected services through the running application or appropriate runtime checks. Run relevant tests, fix failures, and retest. Confirm the process starts and the application is ready; a successful build alone is not a launch. Do not mark the task complete without an actual launch. If a genuine technical blocker prevents launch, report the exact blocker and clearly mark launch as blocked; never claim an unperformed launch or test.

## 4 Engineering Disciplines

- **Autonomous Engineering Instruction:** Activate all 36 listed disciplines for every task. Each engineer must independently discover its full professional responsibilities, assess the task and project, identify and execute all relevant contributions and improvements within its scope, and coordinate with the other engineers. No discipline may be silently skipped; avoid irrelevant changes, duplication, and conflicts. Do not wait for the user to define duties or steps.

| No. | Discipline | No. | Discipline | No. | Discipline | No. | Discipline |
|---:|---|---:|---|---:|---|---:|---|
| 1 | Architecture Engineer | 2 | Systems Engineer | 3 | Backend Engineer | 4 | Frontend Engineer |
| 5 | UI UX Engineer | 6 | AI ML Engineer | 7 | Data Engineer | 8 | Database Engineer |
| 9 | API Integration Engineer | 10 | Security Engineer | 11 | Privacy Engineer | 12 | Performance Engineer |
| 13 | Reliability Engineer | 14 | QA Test Engineer | 15 | DevOps Engineer | 16 | Build Toolchain Engineer |
| 17 | Release Engineer | 18 | Cloud Engineer | 19 | Network Engineer | 20 | Observability Engineer |
| 21 | Configuration Engineer | 22 | Backup Recovery Engineer | 23 | Requirements Engineer | 24 | Technical Lead Engineer |
| 25 | Code Review Edit Engineer | 26 | Knowledge Engineer | 27 | Operations Incident Engineer | 28 | Accessibility Engineer |
| 29 | Localization Engineer | 30 | Scalability Engineer | 31 | Cybersecurity Engineer | 32 | Data Analysis Engineer |
| 33 | Data Science Engineer | 34 | QA Automation Engineer | 35 | Robotics Engineer | 36 | Resources Engineer |  |  |  |  |

## 5 Task Final Report

- **Background:** Use solid black (`#000000`) for the report and all table cells.
- **Automatic Report:** After every completed task, generate the Task Final Report with a concise summary and actual completion, verification, build, and launch results. Use real-time evidence only; never invent results or claim unperformed work.
- **BEFORE / AFTER:** BEFORE shows existing main feature titles; if absent, show `Missing`. AFTER shows added or integrated main feature titles. No descriptions or versions.
- **ENGINEER SUMMARY:** Show each contributing engineer title and one short task-specific contribution.
- **TESTING SUMMARY:** Show only executed testing types and tested child-feature titles. MATRIX contains actual numeric values and units. STATUS is `PASS` or `FAIL`.
- **EXECUTION SUMMARY:** Show only build, development, launch, and application-performance activity. Do not repeat testing types, test features, database checks, or API tests already covered by Testing Summary.
- **EXECUTION ORDER:** List execution steps in actual sequence: Debug first, then Build, and EXE Launch last. Keep EXE Launch as the final execution item.
- **METRIC:** Show real-time measured values and units only.
- **EXECUTION STATUS:** Show `PASS`, `FAIL`, or `WORKING` for each execution item.
- Never show sample values as real results. Omit unavailable measurements or mark their status accurately.

- **Dynamic Table:** Add or remove rows according to actual task data; do not force fixed dimensions.
<table align="center" bgcolor="#000000">
  <tr><th color="#FFFFFF" colspan="12" align="center" bgcolor="#000000">Task Final Report</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="6" bgcolor="#000000">BEFORE</th><th color="#FFFFFF" align="center" colspan="6" bgcolor="#000000">AFTER</th></tr>
  <tr><td color="#FFFFFF" align="center" colspan="6">[Existing Features] / Missing</td><td color="#FFFFFF" align="center" colspan="6">[Updated Features]</td></tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">ENGINEER SUMMARY</th></tr>
  <tr>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Contribution]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Contribution]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Contribution]</td>
  </tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">Testing Summary</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">TESTING TYPE</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">TESTING FEATURE</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">MATRIX</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">STATUS</th></tr>
  <tr><td color="#FFFFFF" align="center" colspan="3">[Test Category]</td><td color="#FFFFFF" align="center" colspan="3">[Tested Component]</td><td color="#FFFFFF" align="center" colspan="3">[Performance Value]</td><td color="#FFFFFF" align="center" colspan="3">[Test Result]</td></tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">Execution Summary</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="4" bgcolor="#000000">EXECUTION</th><th color="#FFFFFF" align="center" colspan="4" bgcolor="#000000">METRIC</th><th color="#FFFFFF" align="center" colspan="4" bgcolor="#000000">STATUS</th></tr>
  <tr>
    <td color="#FFFFFF" align="center" colspan="4">[Execution Step]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Measured Value]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Execution Result]</td>
  </tr>
</table>
