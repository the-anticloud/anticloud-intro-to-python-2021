# Educators — INTRO_TO_PYTHON_2021

**Project:** INTRO_TO_PYTHON_2021  
**Category:** MINING  
**Upstream:** see BENCH.json  
**Pinned commit:** `a08dd274ca5ed59b0133c6304ecffe180d1177cc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7fd47426b3312b397d684d1ea8486133b31af0e79c6611d0636385a7b8cc4ca8`  
**Date:** October 2026

## Teaching with INTRO_TO_PYTHON_2021

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `7fd47426b3312b397d684d1ea8486133b31af0e79c6611d0636385a7b8cc4ca8` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
