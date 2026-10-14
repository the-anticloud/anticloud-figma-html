# Students — FIGMA_HTML

**Project:** FIGMA_HTML  
**Category:** DESIGN_TOOLS  
**Upstream:** https://github.com/BuilderIO/figma-html  
**Pinned commit:** `2b244343ba3fcc1a2de50fa652e13833e78e36f9`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `94046b77bc64846ed187903744a63212e941fb6872b75c2544295b04180f2e1d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `2b244343ba3fcc1a2de50fa652e13833e78e36f9`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `94046b77bc64846ed187903744a63212e941fb6872b75c2544295b04180f2e1d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
