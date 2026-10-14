# Students — PIMATIC

**Project:** PIMATIC  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/pimatic/pimatic  
**Pinned commit:** `ae159b0568626e67a13ef7128284424bd74cc7ef`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `64844340f1b32e0afb1553cfab06d3ee03f3e16620657c75aa44479dfb20524e`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ae159b0568626e67a13ef7128284424bd74cc7ef`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `64844340f1b32e0afb1553cfab06d3ee03f3e16620657c75aa44479dfb20524e`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
