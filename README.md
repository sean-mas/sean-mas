# Sean Kress

**Product engineer working on LLM systems and how to evaluate them.**

Six years shipping software products in regulated, data-heavy environments: the
kind where a model's output has to survive an auditor, not just a benchmark. I
spent those years deciding what got built and writing the requirements for it.
I am now building and shipping it myself.

Berlin based. Python, FastAPI, PostgreSQL, PyTorch. Open to remote.

## What I work on

**Evaluation and observability for AI systems.** The gap that got me interested:
published estimates of how much AI coding assistants actually help range from
**-19%** (METR's randomised trial) to **+9,200%** (a widely shared single-developer
experiment). Both numbers come from serious people. The field has no shared
measuring device, so every claim is an anecdote.

That is the problem I want to work on: the instruments that turn model behaviour
into something you can measure, compare, and defend to somebody who is not in the
room.

## Projects

| Project | What it does | The finding |
| --- | --- | --- |
| [**shap-vs-captum-benchmark**](https://github.com/sean-mas/shap-vs-captum-benchmark) | Systematic comparison of two explainability frameworks on a fine-tuned BERTweet sentiment model, across faithfulness, robustness, token agreement, and cost | SHAP explanations are far more faithful (6.9x deletion-AUC ratio vs near-random) and more stable under perturbation. Captum is 1.37x faster, not the 2x I predicted. Ships a hybrid serving recommendation: Captum for interactive latency, SHAP for audit trails |
| [**churn-aware-repricing**](https://github.com/sean-mas/churn-aware-repricing) | Agent-based simulation of a fee-repricing campaign in wealth management, derived from a production AI product I was responsible for | Phasing the increase captures 77% of the revenue upside for half the client losses. Roughly 50% more revenue per client sacrificed |
| [**undervalued-homes-king-county**](https://github.com/sean-mas/undervalued-homes-king-county) | Hypothesis-driven analysis of 21k home sales, framed around a value-add investor persona, ending in a client-facing deck | Two of the three hypotheses I set out to test did not hold. The signal that survived was homes priced below their local comparables, validated against 175 repeat sales |

A note on all three: each one ends in a decision, not an accuracy score. That is
the habit I brought from product work and the thing I am least willing to drop.

## Currently building

**Agent Trace Lab**, my master's thesis artifact and an open-source workbench. It
records what an AI coding agent actually did (Claude Code hooks plus
OpenTelemetry), checks the run against quality gates, and makes the session
inspectable: timeline, trajectory graph, session scorecard.

The part I have not seen anywhere else is treating gate results as first-class
trace events overlaid on the agent's trajectory, so you can answer where the time
and money went, how much was rework, and whether a guardrail caught the problem
or a human did.

Python, FastAPI, PostgreSQL, Next.js, TypeScript, Docker.

## Background

- **Product:** requirements engineering (CPRE), product ownership (CSPO),
  stakeholder management, product analytics
- **Shipped:** LLM features and agent evaluation workflows in wealth management,
  a cloud landing zone spanning 100+ services, AI route optimisation in logistics
- **Studying:** M.Sc. Data Science and Management (DBU Berlin), alongside a
  full-time AI engineering programme
- **Languages:** German and English native, Spanish fluent

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/sean-kress-115ba0133/)
