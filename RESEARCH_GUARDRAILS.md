# Research Guardrails for Future Projects

These rules apply to substantial scientific, technical, numerical, or exploratory research projects. They should not slow down ordinary coding, writing, planning, or everyday tasks.

## Before heavy work

1. Validate the scientific question first.
2. Perform a novelty/prior-art check.
3. Ask the “so what?” question.
4. Identify the smallest meaningful publishable claim.
5. Prefer an early human domain-expert reality check before large compute.

## During the project

6. One major stage should answer one narrow question.
7. Every major stage needs:
   - a bounded resource budget;
   - explicit PASS criteria;
   - explicit STOP criteria;
   - a clear decision enabled by the result.
8. Prefer analytic checks and cheap falsification before expensive simulation.
9. Do not build general platforms, orchestration, provenance, or dashboards unless the current scientific decision needs them.
10. Use strong review models only at load-bearing gates.
11. Avoid audit-of-audit loops unless they can change a scientific decision.
12. Separate:
   - scientific question;
   - implementation;
   - numerical validation;
   - diagnostics;
   - provenance;
   - review.

## Interpretation rules

13. Numerical/control failure is not a negative physical result.
14. Failure to prove is not disproof.
15. Small absolute error is not acceptable merely because it is small; check scaling/convergence.
16. Multiple AI agents agreeing is not independent validation.
17. Hashes prove identity/integrity, not scientific truth.
18. A sophisticated workflow does not imply scientific significance.

## Stop conditions

19. If a proof route fragments into several independent hard unresolved problems, stop and reassess rather than automatically creating another repair stage.
20. If the next step is still “explore broadly” after several stages, the question is probably not narrow enough.
21. Ignore sunk cost.
22. Before another major compute cycle, ask:

> If this project disappeared tomorrow, what potentially new knowledge would the world lose?

If the answer is vague, do not launch heavy research.

## Scaling rule

Scale research infrastructure only after the scientific value of the underlying claim is established.