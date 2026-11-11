# LeaseServe — supplementary material

Supplement to *Coverage, Not Freshness: Authorized Vector Search under Policy Churn*
(ICDE 2027 Research Track).

- [`supplement.pdf`](supplement.pdf) — 16 pages, 30 tables, 7 figures.

## What this is, and what it is not

This PDF is **measurement detail, not an appendix**. The 12-page paper is
self-contained: it defines the model, states Lemma 1, Theorem 1 and the three
propositions, and argues each of them where it is stated. This document contains
no proofs and no argument the paper depends on; every item in it is either a
detail of a number quoted in the paper or a reproduction note. Section
"What moved here" (p. 1 of the PDF) is the file's own inventory.

A reviewer does not need to open this file to follow the paper's argument.

## Contents

- Architecture figure and lease timeline (mechanics the paper describes in words).
- The full-size evaluation figure, the per-role HNSW table, the three-laws table and the
  dead-fraction grid.
- Baseline protocol, the HoneyBee run, and the measurement-variance record.
- Mechanism ablation and the deployment boundary, with the five-arm table and the p95 condition.
- Repair-versus-rebuild, recovery and replay, and the certificate-fault experiments.
- Known limits of the supplement itself.

## Related repository

Code, ACL inputs, raw result logs and reproduction scripts:
<https://github.com/Cybing521/LeaseServe-Experiments>

No manuscript source (LaTeX) is hosted in this repository.
