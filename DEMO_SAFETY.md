# Assignment 9 — isolated, non-deployed dependency security demo

**Intentional insecure dependency: lodash@4.17.15.**

This repository exists only to demonstrate GitHub Dependabot vulnerability detection, CVSS/severity, patched versions, and automated updates for a course assignment.

- Do not install, execute, build, or deploy the vulnerable package.
- Do not reuse this package manifest in production.
- This is a controlled negative test, separate from the Assignment 8 project.
- After screenshots, upgrade lodash to a patched version (at least 4.17.21) and verify that GitHub reports the finding resolved, or delete the repository after evidence is captured.
- Security alerts depend on GitHub repository settings. Enable Dependency graph, Dependabot alerts and Dependabot security updates.
