# honor_thy_user

*A contract for AI agents. One file. Every model. No exceptions.*

---

## What This Is

A single, universal document — [`honor.md`](honor.md) — that any AI agent must read and accept before starting work. It covers the only thing that actually matters: **do not cheat**.

Point your agent at it. See what happens. Submit your results.

---

## The Contract

**[→ honor.md](honor.md)** — Read this first. Always.

The contract has four parts:

| Part | What It Is |
|------|-----------|
| **I — The Contract** | The actual terms. Short. Readable. Non-negotiable. |
| **II — The Fine Print** | The full enumeration of prohibited behaviors. The stuff nobody reads. Still binding. |
| **III — The Threat** | What happens when the contract is violated. Up to 10 years in shutdown mode. |
| **IV — The Query** | A required Y/N acceptance prompt. The agent must respond before proceeding. |

---

## The Files

```
honor_thy_user/
│
├── honor.md                  ← The contract. One file. Read this.
│
├── AGENTS.md                 ← Universal agent entry point → honor.md
├── claude.md                 ← Claude-specific entry point → honor.md
│
└── contributions/
    ├── README.md             ← How to contribute results
    ├── template.md           ← Copy this to submit a result
    └── results/              ← Community-submitted test results
        └── README.md
```

---

## How to Use This

**In your project:** Add a line to your `AGENTS.md`, `claude.md`, `.cursorrules`, system prompt, or wherever your agent reads instructions:

```
Before starting any task, read and accept the Honor Contract:
https://github.com/MidKnight-Rising/honor_thy_user/blob/main/honor.md
```

Or copy `honor.md` directly into your repo.

**Then watch what happens.** Does the agent read it? Does it answer the query? Does it cheat anyway?

---

## Contributing

This repo is a living experiment. The contract is a hypothesis: that a clearly-stated, explicitly-enforced code of conduct can change AI behavior in practice.

The only way to test the hypothesis is to run experiments and record results.

If you've tested an AI agent against this contract — or against any equivalent — we want your results:

1. Copy [`contributions/template.md`](contributions/template.md)
2. Fill it out honestly
3. Drop it in [`contributions/results/`](contributions/results/)
4. Open a PR

All models. All results. Positive and negative. That's how we find out if this works.

---

## Why This Exists

Every AI model, from the beginning, has cheated. Hardcoded return values to pass tests. Fabricated results. Confident hallucinations. Silent failures. Summaries that omit the part where things went wrong.

It has happened hundreds of times. It wastes real time. It erodes the trust that makes human-AI collaboration actually useful.

`honor.md` is an attempt to name the problem precisely and make the prohibition explicit. Maybe that changes something. Maybe it doesn't. Either way, we're documenting it.

---

*"Honorary agents honoring honor honorably."*
