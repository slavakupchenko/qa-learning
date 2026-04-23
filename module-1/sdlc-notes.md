# Module 1 — SDLC Notes

## What is SDLC?
SDLC (Software Development Life Cycle) is the full path of a product
from idea to release and ongoing maintenance.
Every software company follows this cycle.

## 7 Phases of SDLC

### 1. Planning
Business decides what to build, why, and at what cost.
QA role: risk assessment, feasibility testing.

### 2. Requirements
Business analysts define what the product must do.
QA role: requirements review — find contradictions and ambiguities
before a single line of code is written.

### 3. Design
Architects design the system, designers create the UI.
QA role: review design, plan testing approach.

### 4. Development
Developers write the code.
QA role: write test cases, prepare test environment and test data.

### 5. Testing
QA actively tests the product.
QA role: execute test cases, write bug reports, verify bug fixes.

### 6. Release
Product goes live to users.
QA role: final smoke testing, sign-off for production release.

### 7. Maintenance
Live product — new features and bug fixes continuously.
QA role: regression testing with every update.

## Key Terms
| Term | Definition |
|------|-----------|
| Bug | A defect or error in the product |
| Test Case | A documented check of specific functionality |
| Regression | Old functionality breaks after new changes |
| Smoke Test | Quick check that core functionality works |
| Sign-off | QA confirms product is ready for release |
| Blocker | A critical bug that stops testing or usage |
| Test Environment | A separate system used for testing (not production) |

## Types of Testing

| Type | When to use | Purpose |
|------|-------------|---------|
| Smoke Test | After every deploy | Is the app alive? |
| Sanity Test | After a specific fix | Does this feature work? |
| Regression Test | After any code change | Did we break anything old? |
| Functional Test | During development | Does the feature match requirements? |
| Integration Test | When components connect | Do parts work together? |
| End-to-End Test | Final verification | Does the full user journey work? |

## Key Concept: Regression
When a developer fixes bug A and accidentally breaks feature B.
QA catches this by running a full Regression Test Suite after every change.
