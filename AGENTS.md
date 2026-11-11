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

- **Background Color:** Always render the entire report and every table cell with a solid black background (`#000000`); never use another background color.

- **Task Completion & Report:** After every completed task, automatically generate the Task Final Report table and provide a concise summary of what changed and the actual completion, verification, build, and launch status. Use only the current task's real-time data and evidence; never invent results or report unexecuted checks as completed.
- **BEFORE ONLY / AFTER ONLY:** BEFORE ONLY shows existing main feature titles only; if a feature is absent, show only `Missing`. AFTER ONLY shows integrated or added main feature titles only. No versions or descriptions.
- **ENGINEER SUMMARY ONLY:** Show each contributing engineer title with one short contribution describing only the work performed by that engineer on this task.
- **TESTING TYPE ONLY:** Show only the titles of testing types actually executed, such as Unit Testing, Integration Testing, and End-to-End Testing.
- **TESTING FEATURE ONLY:** Show only the titles of child features actually tested under the relevant main feature. No descriptions.
- **MATRIX ONLY:** Show only actual numeric measurements and units (e.g., `20 ms`, `120 ms`, `1.5 sec`, `95%`). Do not show metric names or descriptions.
- **STATUS ONLY:** Show only the actual status: `PASS` or `FAIL`.
- **BUILD & LAUNCH ONLY:** Show only actual build, debug, EXE launch, and startup-time titles/results.
- **SYSTEM PERFORMANCE ONLY:** Show only measured system-performance metric names and their actual values with units. No descriptions.
- Never invent results or report unexecuted checks as completed.

- **Dynamic Table:** Populate the table from actual task data; add rows and columns as needed, with no fixed dimensions. Let its width and height grow automatically to fit all generated content.
<table align="center" bgcolor="#000000">
  <tr><th color="#FFFFFF" colspan="12" align="center" bgcolor="#000000">Task Final Report</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="6" bgcolor="#000000">BEFORE ONLY</th><th color="#FFFFFF" align="center" colspan="6" bgcolor="#000000">AFTER ONLY</th></tr>
  <tr><td color="#FFFFFF" align="center" colspan="6">[Feature title / Missing]</td><td color="#FFFFFF" align="center" colspan="6">[Main feature title]</td></tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">ENGINEER SUMMARY ONLY</th></tr>
  <tr>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Short contribution]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Short contribution]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Short contribution]</td>
  </tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">Testing Summary</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">TESTING TYPE ONLY</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">TESTING FEATURE ONLY</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">MATRIX ONLY</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">STATUS ONLY</th></tr>
  <tr><td color="#FFFFFF" align="center" colspan="3">[Executed test category]</td><td color="#FFFFFF" align="center" colspan="3">[Tested child feature title]</td><td color="#FFFFFF" align="center" colspan="3">[Numeric value + unit]</td><td color="#FFFFFF" align="center" colspan="3">[PASS / FAIL]</td></tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">Build & Runtime Summary</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="6" bgcolor="#000000">BUILD & LAUNCH ONLY</th><th color="#FFFFFF" align="center" colspan="6" bgcolor="#000000">SYSTEM PERFORMANCE ONLY</th></tr>
  <tr>
    <td color="#FFFFFF" align="center" colspan="6">[Actual build / debug / EXE launch result]</td>
    <td color="#FFFFFF" align="center" colspan="6">[Measured CPU / RAM / GPU / runtime metrics]</td>
  </tr>
</table>
