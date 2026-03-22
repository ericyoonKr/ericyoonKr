# 안녕하세요, 윤치호입니다 👋

단국대학교 법학과 졸업 후 단국대학교 AI융합대학 소프트웨어하과 재학중입니다. 

---

## 관심 분야

**형식 방법론 기반 계산법학 (Formal Methods-based Computational Law)**

현재 LLM 기반 리걸 AI의 근본적인 문제는 **게티어 문제(Gettier Problem)**에 있습니다. AI가 잘못된 추론 과정을 거쳐 우연히 올바른 결론에 도달할 수 있는 구조입니다. 법 앞에서 '우연한 정확성'은 정의가 될 수 없습니다.

저의 목표는 법적 추론을 **확률의 영역(LLM)**에서 **수학적 연역의 영역(형식 검증)**으로 이전시키는 것입니다.

---

## 진행 중인 프로젝트

**Formal-Legal-Verifier**
Z3 SMT 솔버를 이용해 법령과 판결 사이의 논리적 정합성을 수학적으로 검증하는 엔진입니다. LLM이 법률 자연어를 SMT-LIB 명세로 변환하면, Z3가 모순·충돌·함의 관계를 판별합니다. 논리적 결함이 있을 경우 UNSAT 코어를 통해 정확한 오류 지점을 도출합니다.

**Legal-to-SMT Framework**
법령의 언어적 모호성을 형식 인코딩으로 제거하는 방법론 연구입니다.

---

## 학력

- 단국대학교 법과대학 법학과 학사 졸업 (2015–2020)
- 단국대학교 AI융합대학 소프트웨어학과 재학 (2024–현재)

---

## 기술 스택

- **언어:** C, C++, Python
- **형식 검증:** Z3 SMT Solver, SMT-LIB, 심볼릭 실행, 정적 분석
- **도메인:** 법학, 법적 추론, 규범 논리, 규제 컴플라이언스
- **OS:** **Arch Linux (btw)**

---

계산법학, 형식 검증, 뉴로심볼릭 AI에 관심 있으신 분이라면 언제든 연락 주세요.

<br>

---
---

<br>

# Hi, I'm Chiho Eric Yoon 👋

I'm a software engineer with a dual background in **Law (LL.B.)** and **Software Engineering**, working at the intersection of formal logic and legal systems.

My core belief: legal reasoning shouldn't be probabilistic — it should be **mathematically provable**.

---

## What I'm Building

### 🔬 Formal-Legal-Verifier
An SMT-based computational law engine that verifies the logical consistency between statutes and judicial verdicts using the **Z3 SMT Solver**.

The fundamental problem with current LLM-based legal AI is what I call the **Gettier Problem in Legal AI** — a system can reach the *correct verdict* through *incorrect reasoning*. In law, accidental correctness isn't justice.

My approach is to move legal reasoning from the domain of **probability** (LLMs) into the domain of **mathematical deduction** (formal verification).

### How it works

**Step 1 — Translate (Neural)**
An LLM acts as a frontend compiler, converting unstructured legal language — statutes, precedents, verdicts — into formal SMT-LIB specifications.

**Step 2 — Verify (Symbolic)**
The Z3 SMT Solver takes those specifications and checks for logical consistency: Are there contradictions between the statute and the verdict? Does the verdict necessarily follow from the law? If not, *why* — and where exactly does the logic break?

**Step 3 — Result**
Either the legal reasoning is formally verified, or the system surfaces the exact **UNSAT core** — the precise logical conflict that makes the argument invalid.

The goal is a *legal debugger*: a tool that doesn't predict what the law says, but **proves** it.

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

**OS:** Arch Linux (btw)

---

## Get in Touch

If you're working on computational law, formal verification, or neuro-symbolic AI — I'd genuinely love to talk.
