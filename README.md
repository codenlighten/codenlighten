# Gregory Ward

**Software engineer: Rust and TypeScript back ends, full-stack web, blockchain tooling, verifiable systems and AI tooling.**
I take scoped fixes and longer engagements. I find the root cause, fix it and confirm the fix with a regression test.

Sites: [codenlighten.org](https://codenlighten.org) · [smartledger.technology](https://smartledger.technology)

## Start here: one repo per skill

These twelve were built as showcase pieces. Each has CI, tests that were checked by breaking the code on purpose, and a "Limits" section that says what is not covered.

| Skill | Repo | What it shows |
|---|---|---|
| Rust back end | [rust-api-service](https://github.com/codenlighten/rust-api-service) | axum, SQLite, argon2, signed tokens, per-user isolation, problem+json, a measured load test |
| Node / TypeScript + Postgres | [ts-api-starter](https://github.com/codenlighten/ts-api-starter) | Multi-tenant API, idempotency keys, cursor pagination, a migration runner, tests on a real database |
| Cloud (AWS, Terraform) | [aws-signing-service](https://github.com/codenlighten/aws-signing-service) | A signing API on a KMS key behind IAM-authorised API Gateway and Lambda, tested without an AWS account and run once on a real one |
| Full stack and billing | [saas-fullstack-demo](https://github.com/codenlighten/saas-fullstack-demo) | Next.js and Stripe Checkout in test mode, verified and idempotent webhooks |
| Front end and data viz | [data-dashboard](https://github.com/codenlighten/data-dashboard) · [live demo](https://codenlighten.github.io/data-dashboard/) | React, TypeScript, accessible SVG map and charts over a live public feed, browser tests |
| AI / LLM tooling | [llm-tooling-lab](https://github.com/codenlighten/llm-tooling-lab) | Tool-use agent loop, cost budgets, response cache, evaluation harness, all testable offline |
| Debugging method | [root-cause-casebook](https://github.com/codenlighten/root-cause-casebook) | Nine constructed bug cases in five languages: failing test, diagnosis, fix, regression test |
| Language tooling (Rust + WebAssembly) | [mini-language-lab](https://github.com/codenlighten/mini-language-lab) · [live demo](https://codenlighten.github.io/mini-language-lab/) | A small process language: recovering parser, validator with suggestions, comment-preserving formatter, in a React editor with a diagram |
| Databases (PostgreSQL) | [postgres-patterns](https://github.com/codenlighten/postgres-patterns) | Seven studies, each demonstrated by tests: constraints, isolation anomalies, a job queue, pagination, indexes, row-level security and safe migrations, with measured results and their limits |
| Databases (MongoDB) | [mongodb-patterns](https://github.com/codenlighten/mongodb-patterns) | Eight studies, each demonstrated by tests: validation, modelling, atomic updates, transactions, a job queue, indexes by keys examined, pagination and migrations |
| Security (verifiable records) | [tamper-evident-log](https://github.com/codenlighten/tamper-evident-log) | A signed, hash-chained log with Merkle checkpoints and an offline verifier, with a table of attacks it detects and the ones it cannot |
| Security (post-quantum signatures) | [pq-signatures-demo](https://github.com/codenlighten/pq-signatures-demo) | A signing component using a third-party ML-DSA library alongside Ed25519, where both must verify; checked against NIST's test vectors in two libraries, with an attack matrix. A demonstration, not audited |

## Blockchain

| Area | Repo | What it is |
|---|---|---|
| Bitcoin SV primitives | [smartledger-bsv-core](https://github.com/codenlighten/smartledger-bsv-core) | Keys, scripts, transactions and SPV in JavaScript with types. CI replays the reference node's own script test file (bitcoin-sv v1.2.2): all 1483 rows agree on accept or reject with no wrong error reason (109 of the 600 rejections use a documented, narrower error name) |
| BSV Script | [scriptmin](https://github.com/codenlighten/scriptmin) | Bitcoin Script minimiser: byte profiler, stack scheduler and superoptimiser |
| Bitcoin SV formal methods | [bsv-lean-proofs](https://github.com/codenlighten/bsv-lean-proofs) | Lean 4 reference semantics, theorems and conformance vectors for a BSV node |
| Solidity | [solidity-proof](https://github.com/codenlighten/solidity-proof) | ERC-20, ERC-721 and an upgradeable vault with Hardhat and Foundry tests, fuzzing and invariants, a gas study and static analysis. Demonstration code, not audited |

## Deeper systems work

| Area | Repo | What it is |
|---|---|---|
| Rust migration | [node-to-rust-migration-lab](https://github.com/codenlighten/node-to-rust-migration-lab) | Node.js to Rust behind the same API, with a behaviour-parity harness and automatic rollback |

Many older repos on this account are experiments and forks. The ones above are the ones to judge me by.
