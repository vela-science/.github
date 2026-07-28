# Vela Science

Vela is an open scientific-state substrate: version control for what is
claimed, submitted, verified, decided, corrected, and ready to do next.

The core loop is deliberately small:

```text
inspect → attempt → submit → verify → decide → continue
```

Producers produce. Verifiers report. Authorized reviewers decide. Events
record. Replay derives standing. Readers explain.

## Product

- **[vela](https://github.com/vela-science/vela)** — the public product
  monorepo: Rust CLI and protocol implementation, TypeScript protocol SDK,
  Canopus bounded producer, schemas, conformance fixtures, and release
  automation.
- **[Vela Observatory](https://app.vela.space)** — a read-only projection of
  exact public Frontier state. It cannot sign, approve, or mutate scientific
  records.
- **[vela.space](https://www.vela.space)** — the product thesis and public
  editorial surface.

Canopus is optional and removable. It can run bounded agent work and submit
evidence through released Vela interfaces, but it is never a scientific
authority.

## Public Frontiers

Each Frontier is a standalone Git custody source with its own clonable history,
exact replay surface, and authorized Decision boundary.

- [Erdős Problems](https://github.com/vela-science/erdos-frontier)
- [Formal Conjectures](https://github.com/vela-science/formal-conjectures-frontier)
- [Quantum Codes](https://github.com/vela-science/quantum-codes-frontier)
- [Sidon Sets](https://github.com/vela-science/sidon-frontier)

Verifier success is evidence, not acceptance. No model belongs in the
repository-authority or human Decision path.
