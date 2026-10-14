# Educators — PIMATIC

**Project:** PIMATIC  
**Category:** CONSUMER_APPLIANCES  
**Upstream:** https://github.com/pimatic/pimatic  
**Pinned commit:** `ae159b0568626e67a13ef7128284424bd74cc7ef`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `64844340f1b32e0afb1553cfab06d3ee03f3e16620657c75aa44479dfb20524e`  
**Date:** October 2026

## Teaching with PIMATIC

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `64844340f1b32e0afb1553cfab06d3ee03f3e16620657c75aa44479dfb20524e` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
