# Ethics — INTRO_TO_PYTHON_2021

**Project:** INTRO_TO_PYTHON_2021  
**Category:** MINING  
**Upstream:** see BENCH.json  
**Pinned commit:** `a08dd274ca5ed59b0133c6304ecffe180d1177cc`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7fd47426b3312b397d684d1ea8486133b31af0e79c6611d0636385a7b8cc4ca8`  
**Date:** October 2026

## Position

INTRO_TO_PYTHON_2021 is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
