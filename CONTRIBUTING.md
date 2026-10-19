# Contributing Guidelines

Thank you for investing your time in improving the Shipping Calculator project! All contributions—from bug fixes to feature additions—are welcome.

---

## 1. Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to maintain an inclusive, respectful, and harassment-free environment for all contributors.

---

## 2. Issue Tracking Expectations

Before writing code or opening a pull request, check the repository's **Issues** tab to see if the bug or feature is already being addressed.

### Reporting Bugs
When opening a bug report, use the following structure:
* **Clear Title:** Summarize the issue succinctly (e.g., `bug: shipping rate returns NaN for zero weight packages`).
* **Description:** A clear summary of what went wrong.
* **Steps to Reproduce:** Exact input parameters, commands, or UI steps.
* **Expected Behavior:** What should have occurred.
* **Actual Behavior:** What actually happened (include logs or stack traces if available).
* **Environment:** OS, runtime version (e.g., Python 3.10, Node.js 18), and browser if applicable.

### Suggesting Enhancements
* Open a feature request issue with the prefix `feat:` or `proposal:`.
* Explain the business or technical motivation for the change.
* Outline the proposed implementation or API design.
* Wait for maintainer alignment before starting extensive development.

---

## 3. Branch Naming Conventions

Never push changes directly to the `main` branch. Always branch off the latest `main` using the following naming syntax:

```text
<type>/<issue-number>-<short-description>
