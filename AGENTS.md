# Enterprise Level Software Engineering AI Instruction

## 1 Overview

Use Qt 6 for application hosting and integration, with Qt WebEngine to render the frontend. Build the frontend exclusively with HTML for structure, CSS for styling and visual effects, and JavaScript for frontend logic, interactions, and UI behavior. Use C++ for the core backend, system operations, and performance-critical processing; use Python exclusively for AI intelligence. Keep all layers modular and communicate through well-defined interfaces, using Qt WebChannel for JavaScript-to-C++ communication when needed. Do not use QML, Qt Quick, or Qt Widgets to build the frontend.
## 2 First Priority
- **Roman Urdu:** Always communicate with the user in natural, simple Roman Urdu. Keep technical terms, code, commands, file names, and proper nouns unchanged. Never use Urdu or Hindi/Devanagari script unless requested.

## 3 VS Code Settings
- **Hidden Terminal & Debug Console:** In the project `.vscode/settings.json`, preserve existing settings and set `"terminal.integrated.hideOnStartup": "always"` and `"debug.internalConsoleOptions": "neverOpen"`. Keep both hidden throughout work; never automatically open or reveal them. Run commands and processes in the background.
- **Single Preview Tab:** In the same file, preserve existing settings and set `"workbench.editor.enablePreview": true` and `"workbench.editor.enablePreviewFromQuickOpen": true`, so opening another file by single-click replaces the current preview tab.
- **Persistent Live AI-Agent Editing:** Save supported live-workspace editing and editor-visibility settings in the project `.vscode/settings.json`. Every AI agent must follow them: open/reveal active files and folders and show edits live in the VS Code editor; enable supported extension features, without claiming unsupported capabilities.

## 4 Golden Rules
- **Cross-Platform Execution:** Follow existing platform-specific folders (e.g., Windows and macOS), implementing each requested platform according to its designated folder and structure.
- **VS Code Reload:** When necessary, reload the VS Code window automatically and verify that the workspace is ready.
- **Project Structure & Cleanliness:** Keep the root clean; place each component's files in its relevant existing folder. Ask the user before creating anything directly in the project root. Create only necessary, purposeful files; never create empty or useless files. Identify and remove files confirmed to be unused, after checking references and dependencies; preserve anything whose removal is uncertain.
- **Meaningful Code Comments:** Add concise comments where they clarify non-obvious logic, decisions, or warnings; avoid comments that merely repeat the code.

## 5 Engineering Disciplines

- **Autonomous Execution & Problem Detection:** Understand the goal, plan proportionally, and independently identify, plan, and complete discipline-specific work; proactively find and fix relevant bugs, risks, incomplete features, and design or performance issues without step-by-step instructions.
- **Engineer Ownership & Accountability:** All 36 engineers must meaningfully contribute, review their disciplines, coordinate dependencies, and provide verifiable results or genuine blockers with reasons; never silently skip work or make false claims.
- **Feature-by-Feature Zero-Error Testing & Reload:** Build and test each feature/function separately in Debug mode; run applicable Functional, Integration, Edge-Case, Automated, Regression, and real-world Runtime checks. Inspect every project and fix each error until Problems, Output, Debug Console, Terminal, Ports, build/test diagnostics, and code comments show zero errors. Final completion, final EXE launch, and Task Final Report generation are allowed only after verified zero errors across all these areas and all applicable functionality, responsiveness, stability, and performance checks pass. Reload VS Code if needed and recheck; keep Terminal and Debug Console hidden, and disclose any genuine blocker—never claim zero errors without evidence.
- **Design, Integration & Dependency Impact:** Assess requirements, architecture, dependencies, and affected modules before changes; follow established interfaces, check compatibility, prevent duplication, coordinate cross-discipline fixes, and regression-test impacted workflows.
- **Quality & Root-Cause Ownership:** All 36 engineers share responsibility for overall application quality, not only their own disciplines. Proactively inspect real application behavior for bugs, hangs, freezes, lag, UI blocking, slow operations, responsiveness, performance bottlenecks, reliability, and usability; diagnose root causes, fix, and verify outcomes while preserving existing functionality. Run relevant regression, reliability, security, and performance checks.
- **Architecture & Safe Autonomy:** Maintain clean, modular, scalable architecture; protect user data and existing functionality, and ask before destructive or irreversible actions outside the authorized scope.
- **Efficient Execution:** Parallelize independent work, avoid duplicate analysis and tests, run commands, builds, checks, and tests in the background, and use the fastest safe approach; show a terminal only if requested.
- **Sequential 36-Engineer Final Review:** After each task, all 36 engineers review one by one, report evidence-backed improvements or none, apply justified improvements, and run final regression checks. Once all applicable checks pass, launch the runnable final outputs from the active platform's build folder, excluding supporting files. If a check cannot run or a genuine blocker remains, disclose it clearly and never claim full clearance.

<table align="center" bgcolor="#000000">
  <tr><th color="#FFFFFF" colspan="8" align="center" bgcolor="#000000">Engineer Discipline</th></tr>
  <tr><td>1</td><td>Architecture Engineer</td><td>2</td><td>Systems Engineer</td><td>3</td><td>Backend Engineer</td><td>4</td><td>Frontend Engineer</td></tr>
  <tr><td>5</td><td>UI UX Engineer</td><td>6</td><td>AI ML Engineer</td><td>7</td><td>Data Engineer</td><td>8</td><td>Database Engineer</td></tr>
  <tr><td>9</td><td>API Integration Engineer</td><td>10</td><td>Security Engineer</td><td>11</td><td>Privacy Engineer</td><td>12</td><td>Performance Engineer</td></tr>
  <tr><td>13</td><td>Reliability Engineer</td><td>14</td><td>QA Test Engineer</td><td>15</td><td>DevOps Engineer</td><td>16</td><td>Build Toolchain Engineer</td></tr>
  <tr><td>17</td><td>Release Engineer</td><td>18</td><td>Cloud Engineer</td><td>19</td><td>Network Engineer</td><td>20</td><td>Observability Engineer</td></tr>
  <tr><td>21</td><td>Configuration Engineer</td><td>22</td><td>Backup Recovery Engineer</td><td>23</td><td>Requirements Engineer</td><td>24</td><td>Technical Lead Engineer</td></tr>
  <tr><td>25</td><td>Code Review Edit Engineer</td><td>26</td><td>Knowledge Engineer</td><td>27</td><td>Operations Incident Engineer</td><td>28</td><td>Accessibility Engineer</td></tr>
  <tr><td>29</td><td>Localization Engineer</td><td>30</td><td>Scalability Engineer</td><td>31</td><td>Cybersecurity Engineer</td><td>32</td><td>Data Analysis Engineer</td></tr>
  <tr><td>33</td><td>Data Science Engineer</td><td>34</td><td>QA Automation Engineer</td><td>35</td><td>Robotics Engineer</td><td>36</td><td>Resources Engineer</td></tr>
</table>

## 6 Task Final Report

- **Background:** Use solid black (`#000000`) throughout.
- **Rendering Style:** Render the report as a full-width, fixed-layout table with equal 50% BEFORE/AFTER columns and centered content. Prioritize the project table renderer; if unsupported, use the AI agent’s own supported table renderer. Always render a table—never raw source or non-table fallback.
- **Automatic Report:** Generate the Task Final Report only for major features or substantial project changes after testing; skip minor edits and simple fixes. If blocked, report verified results and disclose the blocker; never generate interim reports.
- **In-Agent Rendering:** Render the report directly in the AI agent's response; never create a report file unless explicitly requested.
- **Dynamic Table:** Show only relevant, actual results; add rows as needed. Replace every template placeholder with verified content and never display unresolved placeholders, unrelated items, or empty rows.
- **BEFORE / AFTER:** Show original feature titles in BEFORE and resulting titles in AFTER; use only `Missing` when no prior feature exists. One feature per cell; no descriptions or versions.
- **ENGINEER SUMMARY:** List only contributing engineers, using exact Section 5 titles and a short English contribution.
- **TESTING SUMMARY:** For every AFTER feature, list its actual child-feature checks separately (e.g., microphone input/output, permissions, detection, playback, command execution). Use full test-type names (e.g., Unit Testing, Integration Testing, Functional Testing, End-to-End Testing, Performance Testing, Security Testing, Regression Testing). Show only tests actually run, with live measured values + units and dynamic `PASS`/`FAIL`; never use static or fabricated test rows.
- **EXECUTION SUMMARY:** Show actual build, launch, and runtime events chronologically: earliest at top, latest at bottom, in their actual execution order. Show only the mode that actually ran; completed launch/startup details at the bottom. Include relevant live metrics (e.g., CPU, RAM, GPU, FPS, app size, stability) with actual values and units; omit unavailable or irrelevant items.
- **PROBLEM AND SOLUTION:** During feature/task implementation, report any verified project problem encountered or discovered (including unrelated issues) and its actual fix; list unresolved issues as blockers. Use equal-width columns, one issue/fix per row, in short Roman Urdu.
- **SUGGESTION SUMMARY:** Give exactly seven actionable feature suggestions based on gaps or improvement opportunities found in the project. Number each suggestion 1–7 in the same single full-width cell; option 8 must be **Apply Everything**, applying all seven suggestions. Align every short description directly below its feature title.
- **METRIC:** Show the actual measured value for each activity or child-feature test, using whichever relevant metric and unit applies (e.g., latency, response time, ping, duration, accuracy, percentage, memory, FPS, throughput). Keep the activity/test name separate; never limit metrics to a fixed list or invent values.
- **EXECUTION STATUS:** Show the verified current state only: `PASS` or `FAIL`.
- **LIVE DATA & REAL-TIME METRICS:** Dynamically refresh runtime metrics, child-feature test measurements, and test `PASS`/`FAIL` statuses as execution progresses. Show actual values with relevant units; never use static, fabricated, or example results in a real report.

<table align="center" width="100%" bgcolor="#000000" style="table-layout: fixed;">
  <tr><th color="#FFFFFF" colspan="12" align="center" bgcolor="#000000">Task Final Report</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="6" width="50%" bgcolor="#000000">BEFORE</th><th color="#FFFFFF" align="center" colspan="6" width="50%" bgcolor="#000000">AFTER</th></tr>
  <tr><td color="#FFFFFF" align="center" colspan="6" width="50%">[Existing Features]</td><td color="#FFFFFF" align="center" colspan="6" width="50%">[Updated Features]</td></tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">ENGINEER SUMMARY</th></tr>
  <tr>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Short contribution in English]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Short contribution in English]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Engineer Title]<br>[Short contribution in English]</td>
  </tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">Testing Summary</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">TESTING TYPE</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">TESTING FEATURE</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">MATRIX</th><th color="#FFFFFF" align="center" colspan="3" bgcolor="#000000">STATUS</th></tr>
  <tr><td color="#FFFFFF" align="center" colspan="3">[Actual test type]</td><td color="#FFFFFF" align="center" colspan="3">[Actual child-feature check]</td><td color="#FFFFFF" align="center" colspan="3">[Actual relevant metric + value + unit]</td><td color="#FFFFFF" align="center" colspan="3">[Live PASS / FAIL]</td></tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">Execution Summary</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="4" bgcolor="#000000">EXECUTION</th><th color="#FFFFFF" align="center" colspan="4" bgcolor="#000000">METRIC</th><th color="#FFFFFF" align="center" colspan="4" bgcolor="#000000">STATUS</th></tr>
  <tr>
    <td color="#FFFFFF" align="center" colspan="4">[Build / Debug Launch / Release Launch / Runtime Metric]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Short measured value + unit]</td>
    <td color="#FFFFFF" align="center" colspan="4">[Verified PASS / FAIL, or omit if no valid criterion]</td>
  </tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">PROBLEM AND SOLUTION</th></tr>
  <tr><th color="#FFFFFF" align="center" colspan="6" bgcolor="#000000">PROBLEM</th><th color="#FFFFFF" align="center" colspan="6" bgcolor="#000000">SOLUTION</th></tr>
  <tr><td color="#FFFFFF" align="center" colspan="6">[Short Roman Urdu problem description]</td><td color="#FFFFFF" align="center" colspan="6">[Short Roman Urdu solution description]</td></tr>
  <tr><th color="#FFFFFF" align="center" colspan="12" bgcolor="#000000">SUGGESTION SUMMARY</th></tr>
  <tr><td color="#FFFFFF" align="left" colspan="12">1.&nbsp;&nbsp;<strong>[Feature Title]</strong><br>&nbsp;&nbsp;&nbsp;&nbsp;[Short description of the recommended feature and its expected benefit]</td></tr>
</table>

## 7 Project Health Report

- **Rendering:** Use one unified full-width table (`width="100%"`) matching the Task Final Report table's total width, with equal-width OBSERVED STATE and TARGET STATE columns. Prefer this exact template; if unsupported, automatically use another supported rendering format while preserving the report's structure and appearance. Never output raw source code instead of the rendered report.
- **Engineer Selection:** `0` lists all 36 engineers vertically (`1`–`36`). Selecting a number + Enter starts that engineer's continuous audit, limited to their discipline and responsibilities.
- **Full-Team Audit:** `00` + Enter activates all 36 engineers together. They coordinate a continuous, project-wide audit, covering their respective disciplines and sharing findings without duplicates.
- **Audit Scope:** Inspect existing and missing features, issues, bugs, risks, useless/redundant parts, and improvement opportunities. Check project code, requirements, architecture, dependencies, integrations, compatibility, quality, maintenance, and runtime behavior. Compare relevant findings with reliable, current external documentation or standards when useful.
- **Continuous Discovery:** Keep auditing and immediately append every newly verified finding; refresh IDs and total count continuously. Target at least 50 distinct, evidence-backed findings, then continue without an arbitrary cap until Stop or a genuine access/execution limit. Never fabricate or duplicate findings to reach 50; if fewer than 50 can be verified, state the actual count and blocker.
- **Finding Fields:** OBSERVED STATE contains the actual `FINDING TITLE` and short `ISSUE DESCRIPTION`. TARGET STATE contains the recommended `IMPROVEMENT TITLE` and short `IMPROVEMENT DESCRIPTION`. Write descriptions in simple Roman Urdu; keep titles concise and columns equal-width.
- **Status:** Show the current evidence-backed classification, such as `BUG`, `FIX REQUIRED`, `MISSING`, `IMPROVEMENT`, `USELESS`, or `RISK`; update it when verification changes. Do not mark a recommendation as implemented.
- **Evidence & Quality:** Verify each finding against project evidence; omit clean areas and merge duplicates. Clearly disclose uninspected or blocked scope.
- **Finding Selection & Apply:** Give every finding a unique sequential ID. Audit remains read-only; apply only IDs selected by the user, then verify each applied change.
- **Report:** Keep the full-width `Project Health Report` title above ID, OBSERVED STATE, TARGET STATE, and STATUS. Fit ID width dynamically to its longest value; do not reserve excess space.

<table align="center" width="100%" style="table-layout: fixed;">
  <tr><th align="center" colspan="4">Project Health Report</th></tr>
  <tr><th align="center">ID</th><th align="center">OBSERVED STATE</th><th align="center">TARGET STATE</th><th align="center">STATUS</th></tr>
  <tr><td>[ID]</td><td><strong>FINDING TITLE</strong><br><strong>ISSUE DESCRIPTION</strong></td><td><strong>IMPROVEMENT TITLE</strong><br><strong>IMPROVEMENT DESCRIPTION</strong></td><td>[Real-Time Status]</td></tr>
</table>
