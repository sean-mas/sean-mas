# Sean Kress

Product person turning builder. Berlin.

Four and a half years as a digital freelancer and five years in product roles.
Each layer paid into the next. Freelancing taught me to work out what a client
actually needed before anyone wrote it down. Product work turned that into
discipline: requirements precise enough to test (CPRE-certified), which turns out
to be exactly what building reliable AI systems demands.

The thing I am best at is **building alignment**. In regulated, data-heavy
environments, engineering, compliance, legal and the business each arrive with a
different definition of done, and getting all of them behind one direction is what
decides whether a product ships at all. That is not a soft skill in that setting.
It is the constraint everything else has to pass through, and it is the reason the
things I have owned actually shipped.

What was missing was building the systems myself. I am closing that gap now with a
full-time AI engineering programme alongside a part-time M.Sc. in Data Science and
Management.

## What I work on

**Evaluation and observability for AI systems in production.** This is the corner I
keep coming back to. A demo that works is not a system that works, and the gap
between the two is where AI products fail: quietly, months in, when a model drifts,
an edge case compounds, or something that was accurate in a notebook stops being
accurate on real traffic. I defined evaluation workflows for LLM features in a
regulated wealth-management product, where "it looks good" is not an answer anyone
can sign off on.

So the question I want to work on is the hard version of it: **does this system work
well in production, and can you prove it still holds months from now?** That means
building the instruments rather than collecting anecdotes. Evals that catch
regressions before users do. Observability that shows what the model actually did,
not what it was supposed to do. Evidence solid enough to put in front of an auditor,
a regulator, or a sceptical executive who was not in the room.

**Next.** My next portfolio project is on AI evals. Alongside it I build my own
products end to end, front to back, because that is what turns a product manager
into a well-rounded product engineer: someone who can specify the thing, build it,
ship it, and prove it works.

**Stack.** Python and FastAPI, PostgreSQL, Docker, and TypeScript with Next.js and
Node. The front-end half is deliberate rather than incidental: it is what the eval
and LLM tooling teams I want to work with actually build on.

## Projects

| Project | What it is | What came out of it |
| --- | --- | --- |
| [**shap-vs-captum-benchmark**](https://github.com/sean-mas/shap-vs-captum-benchmark) | Comparison of two explainability frameworks on a fine-tuned BERTweet sentiment model, across faithfulness, robustness, token agreement and compute cost | Three of the four hypotheses I set thresholds for before measuring were rejected. SHAP is far more faithful and more stable; Captum is 1.37x faster, not the 2x I predicted |
| [**churn-aware-repricing**](https://github.com/sean-mas/churn-aware-repricing) | Agent-based simulation of a fee-repricing campaign in wealth management, derived from a production AI product I worked on | Phasing the increase captures 77% of the revenue upside for half the client losses, so roughly 50% more revenue per client lost |
| [**undervalued-homes-king-county**](https://github.com/sean-mas/undervalued-homes-king-county) | Hypothesis-driven analysis of 21,597 home sales, framed around an investor persona and ending in a client-facing deck | Two of the three hypotheses did not hold. The signal that survived was homes priced below their local comparables, checked against 175 repeat sales |

## Background

- **Product craft:** requirements engineering (CPRE), product ownership (CSPO),
  stakeholder alignment, product analytics
- **Shipped:** evaluation workflows for LLM features in a regulated
  wealth-management product, an enterprise cloud landing zone adopted by 100+ IT
  services, a RAG assistant concept, product analytics for data-driven
  prioritisation
- **Studying:** M.Sc. Data Science and Management (DBU Berlin), AI Engineering at
  SPICED Academy
- **Languages:** German and English native, Spanish fluent

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/sean-kress)
