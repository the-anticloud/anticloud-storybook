# Educators — STORYBOOK

**Project:** STORYBOOK  
**Category:** DESIGN_TOOLS  
**Upstream:** https://github.com/storybookjs/storybook  
**Pinned commit:** `4cd0a99e248d8c702efe0261a03606c68298acdd`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `accd30bbd73c76cb9f82b7c6772cb69bf84f0ca19ffd0bfeda9999c3cf0eba4b`  
**Date:** October 2026

## Teaching with STORYBOOK

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `accd30bbd73c76cb9f82b7c6772cb69bf84f0ca19ffd0bfeda9999c3cf0eba4b` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
