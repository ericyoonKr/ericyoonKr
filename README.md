# Hi, I'm Chiho Eric Yoon 👋

I'm a software engineer with a dual background in **Law (LL.B.)** and **Software Engineering**

My core belief: legal reasoning shouldn't be probabilistic — it should be **mathematically provable**.

---

## What I'm Building

### 🔬 Formal-Legal-Verifier
An **SMT-based computational law engine** that verifies the logical consistency between statutes and judicial verdicts using the **Z3 SMT Solver**.

The fundamental problem with current LLM-based legal AI is what I call the **Gettier Problem in Legal AI** — a system can reach the *correct verdict* through *incorrect reasoning*. In law, accidental correctness isn't justice.

My approach is to move legal reasoning from the domain of **probability** (LLMs) into the domain of **mathematical deduction** (formal verification).

### How it works

**Step 1 — Translate (Neural)**
An LLM acts as a frontend compiler, converting unstructured legal language — statutes, precedents, verdicts — into formal SMT-LIB specifications.

**Step 2 — Verify (Symbolic)**
The Z3 SMT Solver takes those specifications and checks for logical consistency: Are there contradictions between the statute and the verdict? Does the verdict necessarily follow from the law? If not, *why* — and where exactly does the logic break?

**Step 3 — Result**
Either the legal reasoning is formally verified, or the system surfaces the exact **UNSAT core** — the precise logical conflict that makes the argument invalid.

The goal is a ***legal debugger***: a tool that doesn't predict what the law says, but **proves** it.

---

## Research Interest

**Formal Methods-based Computational Law**

Specifically, I'm exploring:
- Encoding normative legal logic into SMT-LIB
- Eliminating linguistic ambiguity in statutes through formal symbolic representation
- Building a neuro-symbolic pipeline where LLMs handle the messy natural language layer, and formal solvers handle the proof layer

---

## Background

- **B.S. Law (LL.B.)** — Dankook University, 2015–2020
- **B.S. Software Engineering** — Dankook University, 2024–present

The law degree wasn't a detour. Understanding how legal arguments are actually constructed — how statutes interact, how courts reason — is what makes the formalization problem tractable.

---

## Tech Stack

**Languages:** C, C++, Python

**Formal Methods:** Z3 SMT Solver, SMT-LIB, Symbolic Execution, Static Analysis

**Domain:** Jurisprudence, Legal Reasoning, Normative Logic, Regulatory Compliance

**OS:** **Arch Linux (btw)**

---

## Get in Touch

If you're working on computational law, formal verification, or neuro-symbolic AI — I'd genuinely love to talk.
