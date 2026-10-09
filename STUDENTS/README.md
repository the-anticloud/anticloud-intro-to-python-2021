# Students — INTRO_TO_PYTHON_2021

**Project:** INTRO_TO_PYTHON_2021  
**Category:** MINING  
**Upstream:** see BENCH.json  
**Pinned commit:** `a08dd274ca5ed59b0133c6304ecffe180d1177cc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7fd47426b3312b397d684d1ea8486133b31af0e79c6611d0636385a7b8cc4ca8`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `a08dd274ca5ed59b0133c6304ecffe180d1177cc`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `7fd47426b3312b397d684d1ea8486133b31af0e79c6611d0636385a7b8cc4ca8`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
