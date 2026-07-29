# Sean Kress

Product person turning builder. Berlin.

Five years in product roles: AI Product Manager at Oliver Wyman, Product Owner at
Axel Springer and at Rhenus Logistics, and a co-founded startup before those. Four
and a half years freelancing as a digital consultant before I moved into product.
Mostly regulated, data-heavy environments, where the work was turning fuzzy ideas
into requirements precise enough to test, and turning technical detail into
something the rest of the room could argue with.

What was missing was building the systems myself. I am closing that gap now: a
full-time AI engineering programme alongside a part-time M.Sc. in Data Science and
Management.

## What I work on

Reading, thinking and building around AI-assisted software development and how to
evaluate it. Two questions that turn out to be the same question: how much do
coding agents actually help, in my own work and in an enterprise codebase, and how
would anyone know?

The gap that got me interested: published estimates of how much AI coding
assistants help range from **-19%** (METR's randomised trial) to **+9,200%** (a
widely shared single-developer experiment). Both numbers come from serious people.
The field has no shared measuring device, so every claim is an anecdote.

That is the problem I want to work on: the instruments that turn model behaviour
into something you can measure, compare, and defend to somebody who is not in the
room.

The current build is **Agent Trace Lab**, an open-source workbench. It records what
an AI coding agent actually did (Claude Code hooks plus OpenTelemetry), checks the
run against quality gates, and makes the session inspectable: timeline, trajectory
graph, session scorecard.

The part I have not seen anywhere else is treating gate results as first-class
trace events overlaid on the agent's trajectory, so you can answer where the time
and money went, how much was rework, and whether a guardrail caught the problem or
a human did.

Python, FastAPI, PostgreSQL, Next.js, TypeScript, Docker.

Alongside that I build my own products end to end. Shipping the whole thing is the
fastest way to find the holes in my stack, and I would rather be a product engineer
who can build the thing than one who can only specify it.

## Projects

| Project | What it is | What came out of it |
| --- | --- | --- |
| [**shap-vs-captum-benchmark**](https://github.com/sean-mas/shap-vs-captum-benchmark) | Comparison of two explainability frameworks on a fine-tuned BERTweet sentiment model, across faithfulness, robustness, token agreement and compute cost | Three of the four hypotheses I set thresholds for before measuring were rejected. SHAP is far more faithful and more stable; Captum is 1.37x faster, not the 2x I predicted |
| [**churn-aware-repricing**](https://github.com/sean-mas/churn-aware-repricing) | Agent-based simulation of a fee-repricing campaign in wealth management, derived from a production AI product I worked on | Phasing the increase captures 77% of the revenue upside for half the client losses, so roughly 50% more revenue per client lost |
| [**undervalued-homes-king-county**](https://github.com/sean-mas/undervalued-homes-king-county) | Hypothesis-driven analysis of 21,597 home sales, framed around an investor persona and ending in a client-facing deck | Two of the three hypotheses did not hold. The signal that survived was homes priced below their local comparables, checked against 175 repeat sales |

## Background

- **Product:** requirements engineering (CPRE), product ownership (CSPO),
  stakeholder management, product analytics
- **Shipped:** evaluation workflows for LLM features in a regulated
  wealth-management product, an Azure enterprise landing zone adopted by 100+ IT
  services, a RAG assistant concept, product analytics at Rhenus
- **Studying:** M.Sc. Data Science and Management (DBU Berlin) and AI Engineering
  at SPICED Academy
- **Before that:** B.A. Intercultural Management and Communication, with semesters
  in Seoul and Xi'an
- **Languages:** German and English native, Spanish fluent

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/sean-kress)
