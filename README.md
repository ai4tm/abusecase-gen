# Agentic Abuse-Case Generator

Multi-persona agent system that auto-generates abuse cases for features based on [OWASP guidelines](https://cheatsheetseries.owasp.org/cheatsheets/Abuse_Case_Cheat_Sheet.html).

## What it is

tm-agents is an open-source tool that runs specialized agents (Business Analyst, Risk Analyst, Penetration Tester, QA, Tech Lead, etc.) to generate, score, and track abuse cases for a feature or application.

## Why

* Capture diverse adversarial perspectives automatically.

* Produce prioritized, actionable abuse cases that fit into user stories, tickets, and CI.

* Surface emergent/run-time abuse cases and tie them to mitigations and tests.

## Key features

* Multi-persona agent orchestration

* Template driven prompts and plug-in agent personas

* Mapping to OWASP, CAPEC, STRIDE, CVSS scoring

* Output formats: JSON, Markdown, JIRA/GitHub comments, and machine-readable artifacts (DFD — Data Flow Diagram annotations)

* CI hooks to attach abuse-case diffs to pull requests


## Agent roles (examples)

* Business Analyst — attacker motivation, value, collateral impact

* Risk Analyst — likelihood, CVSS scoring, compliance notes

* Penetration Tester — exploit steps, PoC ideas, CAPEC mapping

* Tech Lead — architectural impact, mitigations, tradeoffs

* QA / Functional Tester — test cases, detection checks, regression tests


For more info please contact vikramsnarayan@gmail.com
