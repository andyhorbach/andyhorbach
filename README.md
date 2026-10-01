# Andrii Horbach

### Senior QA Engineer

14+ years in software testing across fintech, healthcare, logistics and enterprise systems. I build test strategies that start from risk, not from tooling: identify what can go wrong, decide what deserves testing, and make every automated check traceable to a reason.

## What I do

- Risk-based test strategy and test design
- API testing and automation
- End-to-end testing of business-critical flows
- Database and data-consistency validation
- Negative, boundary, concurrency and idempotency testing
- Defect investigation and root-cause analysis

## Technical focus

- **API automation:** Java, JUnit 5, REST Assured
- **UI / E2E automation:** Playwright, TypeScript
- **Data:** SQL, PostgreSQL
- **Tooling & delivery:** Maven, Git, CI/CD

## Portfolio

Both projects are fully synthetic, built specifically to demonstrate QA reasoning — no employer code or data.

- **[transaction-processing-qa](https://github.com/andyhorbach/transaction-processing-qa)** — risk-based testing of a synthetic payment system: money integrity, idempotency and retries, state-transition coverage, authorization isolation, and an independent database oracle — a risk-traceable REST Assured suite over a real Spring Boot + PostgreSQL service.
- **[medical-system-qa](https://github.com/andyhorbach/medical-system-qa)** — the same risk-first method applied to a synthetic clinic domain: privacy and role-based authorization, patient–record association, and audit-trail validation. Currently at the risk-analysis stage — deliberately, since that is where every project here starts.

## QA approach

These projects follow the same chain: a prioritised risk inventory first, then an explicit contract that resolves the open design decisions, then tests that each name the risk they cover. Test oracles stay independent of the implementation they verify, negative and boundary cases are first-class citizens, concurrency is tested with real parallel requests, and the gaps a suite does *not* cover are documented rather than hidden.

## Currently

Expanding the portfolio with CI quality gates and a second risk-first QA project.
