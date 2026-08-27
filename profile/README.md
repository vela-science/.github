# Vela Science

Vela is version control for scientific state: a Git-native protocol and CLI
for recording what is claimed, submitted, checked, decided, corrected, and
safe to do next.

The core loop is deliberately small:

```text
init → submit → verify → decide → replay
```

Work can happen in any native tool. A Submission retains bounded producer
evidence. A Verification Record reports one scoped check. Only an authorized
Decision changes Standing, and strict replay derives the current state.

## Current ecosystem

- **[Vela Core](https://github.com/vela-science/vela)** owns Protocol 1, the
  Rust CLI, canonical bytes and roots, replay, schemas, conformance, and signed
  releases. `v0.977.6` is current. Signed `v0.977.5` remains immutable history.
- **[Problems](https://github.com/vela-science/problems)** owns the public
  discovery and hosted-work product at [problems.science](https://problems.science).
  Its read projection and WebMCP tools cannot change scientific Standing.
- **[Workbench](https://github.com/vela-science/vela-workbench)** owns local
  activity, native runs, evidence preparation, and explicit handoff to Vela's
  Submission boundary. It holds no Repository authority.
- **[Math](https://github.com/vela-science/math)** is the reference mathematics
  authority Repository: exact Sources, Claims, Verifications, Decisions, and
  replay state under one local trust root.

[vela.space](https://vela.space) is the public editorial surface. Problems,
Workbench, Math, and Core remain separate because discovery, activity,
scientific authority, and protocol execution have different owners.

Git preserves bytes and ancestry. Native scientific tools preserve their own
domain meaning. Vela owns only the exact transition from bounded evidence and
scoped checks into locally governed, correction-aware Standing.

## Repository model

A Repository exists because there is an independent scientific authority, not
because there is another topic. A Frontier is a derived query over unresolved
state; it owns no history, trust root, or protocol identity. Sources preserve
external provenance, and Problems names bounded questions.

The Observatory was the historical name for a derived read surface. Problems
now owns the public read product. No current Observatory application is
deployed at `app.vela.space`.

The former topic repositories are archived historical evidence and are not
part of the current product topology:

- [Erdős Problems](https://github.com/vela-science/erdos-frontier)
- [Formal Conjectures](https://github.com/vela-science/formal-conjectures-frontier)
- [Quantum Codes](https://github.com/vela-science/quantum-codes-frontier)
- [Sidon Sets](https://github.com/vela-science/sidon-frontier)

Verifier success, a model output, a Git commit, and a Web badge are evidence or
publication facts, not acceptance. No model belongs in the human Decision or
repository-authority path.

## Current limits

- Problems source and production remain frozen at
  `532241ba5db565e9ee35e13cbd7eff76393f6475` through the WebMCP challenge
  submission and its subsequent 24-hour exact-SHA stability window.
- The public projection still binds Vela `0.977.3` and a private authenticated
  source-adapter asset. Public reconstruction and the related rights ledger
  remain deferred until the challenge freeze passes.
- The current `vela.space` deployment still comes from private transitional
  `vela-web` source and links Vela `0.977.2`. A rights-safe tiny www extraction,
  deployment parity, licensing closure, and approved legacy cleanup remain
  deferred work.
