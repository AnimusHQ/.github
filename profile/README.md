<p align="center">
    <img src="https://raw.githubusercontent.com/AnimusHQ/.github/main/assets/animus-banner.png" alt="Animus — Freedom is architecture" width="100%" />
</p>

<h1 align="center">Animus</h1>

<p align="center">
  <strong>We build the infrastructure beneath the visible web.</strong>
</p>

<p align="center">
  Protocols · Cryptographic identity · Secure connectivity · Control planes · Developer tooling
</p>

<p align="center">
  <a href="https://github.com/AnimusHQ/link">Animus Link</a>
  ·
  <a href="https://t.me/animuscrew">Community</a>
  ·
  <a href="https://t.me/animus_link_bot">Get access</a>
</p>

---

## Freedom is architecture

The digital world looks weightless from the surface. Underneath it is architecture: identity, trust, protocols, state machines, relays, permissions, failure modes, and thousands of decisions that determine who can connect — and what happens when the system is placed under pressure.

**Animus is an open engineering ecosystem for building that hidden layer deliberately.**

We work where ideas become specifications, specifications become code, and code becomes infrastructure that must survive contact with the real world.

That means documenting assumptions. Defining trust boundaries. Testing invariants. Reviewing cryptography. Measuring failure. Rebuilding weak parts instead of disguising them.

No hype cycles. No black boxes by default. No technology theatre.

Just systems that can be read, questioned, tested, and improved.

---

## What we are building

### [Animus Link](https://github.com/AnimusHQ/link)

Animus Link is a secure connectivity protocol built around self-certifying cryptographic identity, end-to-end encrypted sessions, relay-assisted transport, and invite-scoped private discovery.

The public repository contains:

- the Rust protocol implementation;
- normative protocol specifications;
- conformance vectors and tooling;
- the device daemon and command-line interfaces;
- the managed relay protocol;
- architecture, security, audit, and production-readiness documentation.

> **Current status:** pre-1.0, specification-track. Production v1 has not yet been declared.

The repository distinguishes two layers:

- **Animus Fabric** — identity, wire formats, secure sessions, discovery, transport, and relay primitives;
- **Animus Link** — the operator-facing daemon, command-line tools, and managed relay built over the protocol core.

[Explore Animus Link →](https://github.com/AnimusHQ/link)

### The wider ecosystem

Animus is not a single application. It is a growing set of protocols, implementations, engineering tools, specifications, operational documents, and community surfaces connected by one principle:

> Build systems that are clear enough to understand, strict enough to review, secure enough to trust, and resilient enough to evolve.

New repositories are opened when their scope, security boundaries, documentation, maturity, and licensing are explicit enough for public scrutiny.

---

## How we build

| Principle | What it means in practice |
|---|---|
| **Specification before mythology** | Important behavior is written down as terminology, invariants, interfaces, and conformance requirements. |
| **Evidence before claims** | Implemented behavior, experiments, limitations, and roadmap work are clearly separated. |
| **Security as architecture** | Trust boundaries, authorization, secret handling, failure behavior, and recovery are design inputs — not release-day additions. |
| **Code that can be inspected** | Repositories should be understandable without private tribal knowledge. |
| **Operations are part of the product** | Build, test, deploy, observe, debug, and recover paths must be documented. |
| **Revision is a strength** | Specifications and implementations improve through review, testing, disagreement, and measured change. |

---

## Start here

| You are… | Begin with… |
|---|---|
| **Exploring the protocol** | Read the [Animus Link overview](https://github.com/AnimusHQ/link#animus-link), then continue into its specifications and architecture documents. |
| **Trying the current access experience** | Open the [Animus Link Telegram bot](https://t.me/animus_link_bot). |
| **Following development** | Join the [Animus community](https://t.me/animuscrew). |
| **Contributing code or documentation** | Read the target repository’s README, maturity status, contribution guide, open issues, and security policy before proposing a large change. |
| **Reviewing security** | Start with the repository security model and trust boundaries. Report sensitive findings privately. |

---

## Contribution culture

Useful contributions are not limited to implementation work.

We welcome focused improvements to:

- protocol specifications and terminology;
- architecture and threat-model documentation;
- conformance vectors and test coverage;
- reproducible builds and developer tooling;
- operational runbooks and failure analysis;
- onboarding, examples, diagrams, and translations;
- narrowly scoped code changes with clear validation.

For substantial changes, open an issue or discussion before investing in a large implementation. Pull requests should remain reviewable, include validation where possible, and update documentation when behavior changes.

---

## Security

Security-sensitive reports should **not** be submitted through public issues or public community chat.

Contact: **animusecho@proton.me**

A useful report includes the affected repository and revision, reproduction steps, expected impact, affected configuration, and any logs or proof of concept that are safe to share.

---

## Project maturity and licensing

Every Animus repository should state its own maturity and license. A public repository is not automatically production-ready, and public source visibility does not by itself grant permission to use, modify, or redistribute its contents.

Read the repository README, status documents, security policy, and `LICENSE` file before depending on a project.

---

## Follow the work

- **GitHub:** [github.com/AnimusHQ](https://github.com/AnimusHQ)
- **Community:** [t.me/animuscrew](https://t.me/animuscrew)
- **Animus Link access:** [t.me/animus_link_bot](https://t.me/animus_link_bot)

<p align="center">
  <strong>From idea to protocol. From protocol to code. From code to resilient infrastructure.</strong>
</p>

<p align="center">
  <sub>Freedom is architecture.</sub>
</p>
