# CFB

The buildsytem "Chainsaw For Bureaucracy" or "Clean Fast Build" or whatever you chose to call it.

CFB is a new kind of build system: lean, distributed, and built to cut through the complexity that has crept into modern build tooling.

While others pile on abstraction layers, rule sets, and indirection, CFB takes the opposite path:
clarity, speed, and direct control.

---

## Philosophy

Modern build systems have become bureaucracies — each department adding its own rulebook.
CFB brings back sanity by focusing on three core ideas:

1. Transparency over magic — what you see is what you build.
2. Distributed by design — no central controller; every node is a peer.
3. Composable and minimal — logic, not layers.

---

## Vision

CFB isn’t just another incremental improvement on Bazel or Buck.
It’s a "back to basic", ground-up rethinking of what a build system can be in a decentralized world.

- Deterministic builds without the central bottleneck.
- Shared computation and caching across peers.
- Declarative, data-driven definitions — not macro jungles.

---

## Status

CFB is in early prototype phase.
Expect breaking changes, half-finished features, and occasional sparks from the chainsaw.
Contributions, ideas, and critiques are all welcome.

---

## Building

    git clone https://github.com/igniteit/cfb
    cd cfb
    cargo build --release

Then run:

    ./target/release/cfb --help

---

## Join the Discussion

CFB is part of a broader effort to make build systems distributed, fast, and understandable again.
If that resonates with you, open an issue, start a discussion — or better yet, bring your own chainsaw.

---

## License

MIT — do what you want, just don’t reintroduce bureaucracy.

