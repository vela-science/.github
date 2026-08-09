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

## Product

- **[vela](https://github.com/vela-science/vela)** — the public product
  monorepo: Rust CLI and protocol implementation, portable schemas,
  independent conformance readers and emitters, and release automation.
- **[math](https://github.com/vela-science/math)** — the one live mathematics
  authority Repository: exact Sources, Claims, Verifications, Decisions, and
  replay state under one local trust root.
- **[Vela Observatory](https://app.vela.space)** — a read-only projection of
  exact Repository and Source state. It cannot sign, decide, or mutate
  scientific records.
- **[vela.space](https://www.vela.space)** — the product thesis and public
  editorial surface.

Git preserves bytes and ancestry. Native scientific tools preserve their own
domain meaning. Vela owns only the exact transition from bounded evidence and
scoped checks into locally governed, correction-aware Standing.

## Repository model

A Repository exists because there is an independent scientific authority, not
because there is another topic. A Frontier is a derived query over unresolved
state; it owns no history, trust root, or protocol identity. Sources preserve
external provenance, Problems name bounded questions, and the Observatory is a
disposable Atlas projection.

The former topic repositories are archived historical evidence and are not
part of the current product topology:

- [Erdős Problems](https://github.com/vela-science/erdos-frontier)
- [Formal Conjectures](https://github.com/vela-science/formal-conjectures-frontier)
- [Quantum Codes](https://github.com/vela-science/quantum-codes-frontier)
- [Sidon Sets](https://github.com/vela-science/sidon-frontier)

Verifier success, a model output, a Git commit, and a Web badge are evidence or
publication facts, not acceptance. No model belongs in the human Decision or
repository-authority path.
