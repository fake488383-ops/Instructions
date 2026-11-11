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

- **Single Table:** Present the complete Task Final Report in one compact, blue-styled table. Put every report section and value inside that same table; do not create separate tables or add unnecessary text outside it.
- **BEFORE:** Show only the affected feature title. If the feature did not exist before the task, show **Missing**. If it existed, show its existing feature title. Never show file names, paths, or explanations.
- **AFTER:** Show only the added feature title or the improved feature title/version. Do not add explanations, file names, paths, or filler text.
- **Engineer Summary:** Show only the exact titles of disciplines that materially contributed, with a very short contribution. Do not list idle engineers.
- **Testing Type:** Show only testing categories actually executed, such as Unit Testing, Integration Testing, or End-to-End Testing.
- **Testing Feature:** Show only the tested child-feature names; never repeat the main feature. Include only features actually tested.
- **Metric & Status:** Show compact measured values with units (e.g. 120ms, 1.5s, 38%) and PASS or FAIL for each executed test. Never invent metrics or mark unexecuted tests PASS.
- **Build & Launch:** Show concise actual build, debug, and EXE/application launch results. Mark only actions that actually occurred.
- **System Performance:** Show only measured target-process metrics such as CPU, RAM, GPU, latency, or throughput, with units. Omit unavailable measurements; never estimate.
- **Evidence:** Every reported value must come from the current task's actual project state, test output, build log, runtime, profiler, or monitoring data. Refresh evidence after changes and retest. Never use defaults, cached examples, or invented values.
- Keep every label and value short. Include only information supported by actual work. If a check or measurement was unavailable, state the verification gap briefly inside the table.

<table align="center">
  <tr><th colspan="4" align="center" bgcolor="#17365D">Task Final Report</th></tr>
  <tr><th align="center" colspan="2" bgcolor="#D9EAF7">BEFORE</th><th align="center" colspan="2" bgcolor="#D9EAF7">AFTER</th></tr>
  <tr><td align="center" colspan="2">[Feature title / Missing]</td><td align="center" colspan="2">[Added or improved feature title/version]</td></tr>
  <tr><th align="center" colspan="4" bgcolor="#D9EAF7">Engineer Summary</th></tr>
  <tr>
    <td align="center">[Engineer Title]<br>[Short contribution]</td>
    <td align="center">[Engineer Title]<br>[Short contribution]</td>
    <td align="center">[Engineer Title]<br>[Short contribution]</td>
    <td align="center">[Engineer Title]<br>[Short contribution]</td>
  </tr>
  <tr><th align="center" colspan="4" bgcolor="#D9EAF7">Testing Summary</th></tr>
  <tr><th align="center" bgcolor="#D9EAF7">Testing Type</th><th align="center" bgcolor="#D9EAF7">Testing Feature</th><th align="center" bgcolor="#D9EAF7">Metric</th><th align="center" bgcolor="#D9EAF7">Status</th></tr>
  <tr><td align="center">[Executed test category]</td><td align="center">[Tested child feature]</td><td align="center">[Measured value + unit]</td><td align="center">[PASS / FAIL]</td></tr>
  <tr><th align="center" colspan="4" bgcolor="#D9EAF7">Build & Runtime Summary</th></tr>
  <tr><th align="center" colspan="2" bgcolor="#D9EAF7">Build & Launch</th><th align="center" colspan="2" bgcolor="#D9EAF7">System Performance</th></tr>
  <tr>
    <td align="center" colspan="2">[Actual build / debug / EXE launch result]</td>
    <td align="center" colspan="2">[Measured CPU / RAM / GPU / runtime metrics]</td>
  </tr>
</table>

