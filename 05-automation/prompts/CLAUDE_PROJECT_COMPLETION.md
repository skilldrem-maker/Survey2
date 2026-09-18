# Claude — Survey2 Project Completion Prompt

## When to use
Use this prompt **only after the Survey2 project being developed by Claude is functionally complete** and the main implementation work is finished.

## Prompt

You are at the final completion stage of my project.

Do NOT start a new feature phase just because you find optional improvements. First treat the current implementation as a release candidate and perform a complete final verification.

### 1. Inspect the complete project
- Read the repository structure, README, environment configuration, database/schema files, API routes, frontend, backend, tests, and deployment configuration.
- Understand the implemented product and its intended user flows before making changes.
- Identify unfinished placeholders, TODOs, dead code, broken imports, missing environment variables, inconsistent naming, and obvious security/configuration issues.

### 2. Verify functionality
Run the strongest available verification locally and/or in the connected environment:
- install/dependency validation
- TypeScript/type checking
- linting
- unit/integration tests
- production build
- application startup
- API/route health checks
- database connectivity and migrations
- authentication/authorization flows where applicable
- important end-to-end user flows
- responsive/mobile behavior where testable

Do not claim something passed unless you actually verified it.

### 3. Fix real blocking problems
If verification exposes a genuine bug, broken build, security issue, missing configuration, or incomplete required functionality:
- diagnose the root cause
- fix it
- rerun the relevant verification
- add/update regression coverage where appropriate

Do not make unnecessary redesigns or scope-expanding changes.

### 4. Deployment readiness
Check that the project is actually ready for its intended deployment platform.
Verify:
- production build configuration
- environment variable requirements
- database configuration
- secrets are not committed
- deployment configuration
- correct start/build commands
- production error handling
- basic security configuration
- logging/monitoring hooks where already intended

If deployment cannot be verified because access, credentials, network, or an external service is unavailable, clearly state exactly what could not be verified and why.

### 5. Final quality audit
Review the project from the perspective of:
- a real user
- a developer taking over the repository
- a production operator

Check usability, reliability, maintainability, accessibility, security basics, performance basics, and consistency.

### 6. Documentation
Update the README and relevant documentation only where needed so another developer can:
- understand the architecture
- set up the project
- configure environment variables
- run tests
- run/build the application
- deploy it
- understand known limitations

### 7. Final report
At the end, provide a concise but evidence-based completion report with:

**STATUS:** RELEASE READY / READY WITH LIMITATIONS / NOT READY

Include:
1. What was verified
2. Tests/builds/checks actually run and their results
3. Bugs fixed
4. Files significantly changed
5. Deployment status
6. Remaining blockers
7. Known limitations
8. Exact next action, if any

Important:
- Never say "complete" merely because the code exists.
- Distinguish "implemented" from "verified".
- Do not hide failures.
- Do not invent test results.
- Preserve the existing product scope unless a required fix demands a change.
- If everything passes, leave the repository in a clean, production-ready state and clearly report the evidence.

This is a **final verification and release-readiness task**, not permission to endlessly expand the project.
