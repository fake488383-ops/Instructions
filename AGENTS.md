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

- **Mandatory Output:** After completing and verifying every task, generate and display the fully populated Task Final Report table in the final response. The blueprint alone is not the report.
- **Dynamic Layout:** Create one separate column/cell for every actual feature, engineer, testing type, tested child feature, and reported result as applicable. Never combine multiple items into one cell. Add columns and rows automatically according to the actual data; allow the table height to grow naturally. Do not use fixed column counts, row counts, or heights.
- **BEFORE / AFTER:** Show feature titles only. Use **Missing** in BEFORE when the feature did not exist.
- **Engineer Summary:** Show only contributing engineer titles, each in a separate cell with a short contribution.
- **Testing Summary:** Show only executed testing-type titles and tested child-feature titles. Keep each item in its own cell.
- **Metric / Status:** Show only short measured values with units and **PASS** or **FAIL**. No descriptions.
- **Build & Launch:** Show only concise, actual build, debug, and launch results.
- **System Performance:** Show only measured system metric names and values with units.
- **Appearance:** Use a black table background (**#000000**), white text, and clear subtle borders. Keep section headers readable against the black background. Do not use a blue background.
- Never invent results or report unexecuted checks as completed.

<table align="center" bgcolor="#000000" border="1">
  <tr><th colspan="{DYNAMIC_TOTAL_COLUMNS}" align="center" bgcolor="#202020"><font color="#FFFFFF">Task Final Report</font></th></tr>
  <tr>
    <th colspan="{BEFORE_FEATURE_COUNT}" align="center" bgcolor="#202020"><font color="#FFFFFF">BEFORE</font></th>
    <th colspan="{AFTER_FEATURE_COUNT}" align="center" bgcolor="#202020"><font color="#FFFFFF">AFTER</font></th>
  </tr>
  <tr>
    <td>[One feature title per cell; use Missing if absent]</td>
    <td>[One added/improved feature title per cell]</td>
  </tr>
  <tr><th colspan="{DYNAMIC_TOTAL_COLUMNS}" align="center" bgcolor="#202020"><font color="#FFFFFF">Engineer Summary</font></th></tr>
  <tr>
    <td>[Engineer title]<br>[Short contribution]</td>
    <td>[Repeat one cell per contributing engineer]</td>
  </tr>
  <tr><th colspan="{DYNAMIC_TOTAL_COLUMNS}" align="center" bgcolor="#202020"><font color="#FFFFFF">Testing Summary</font></th></tr>
  <tr>
    <th><font color="#FFFFFF">Testing Type</font></th>
    <th><font color="#FFFFFF">Testing Feature</font></th>
    <th><font color="#FFFFFF">Metric</font></th>
    <th><font color="#FFFFFF">Status</font></th>
  </tr>
  <tr>
    <td>[One executed testing type per cell]</td>
    <td>[One tested child feature per cell]</td>
    <td>[One measured value per cell]</td>
    <td>[PASS / FAIL per test]</td>
  </tr>
  <tr><th colspan="{DYNAMIC_TOTAL_COLUMNS}" align="center" bgcolor="#202020"><font color="#FFFFFF">Build & Runtime Summary</font></th></tr>
  <tr>
    <th colspan="{BUILD_RESULT_COLUMNS}" bgcolor="#202020"><font color="#FFFFFF">Build & Launch</font></th>
    <th colspan="{PERFORMANCE_RESULT_COLUMNS}" bgcolor="#202020"><font color="#FFFFFF">System Performance</font></th>
  </tr>
  <tr>
    <td>[One actual build/debug/launch result per cell]</td>
    <td>[One measured performance metric per cell]</td>
  </tr>
</table>
