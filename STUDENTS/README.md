# Students — STORYBOOK

**Project:** STORYBOOK  
**Category:** DESIGN_TOOLS  
**Upstream:** https://github.com/storybookjs/storybook  
**Pinned commit:** `4cd0a99e248d8c702efe0261a03606c68298acdd`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `accd30bbd73c76cb9f82b7c6772cb69bf84f0ca19ffd0bfeda9999c3cf0eba4b`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `4cd0a99e248d8c702efe0261a03606c68298acdd`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `accd30bbd73c76cb9f82b7c6772cb69bf84f0ca19ffd0bfeda9999c3cf0eba4b`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
