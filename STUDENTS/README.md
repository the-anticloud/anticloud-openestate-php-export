# Students — OPENESTATE_PHP_EXPORT

**Project:** OPENESTATE_PHP_EXPORT  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/OpenEstate/OpenEstate-PHP-Export  
**Pinned commit:** `0aaaaa6132ac199ab12cdc680f91f6ae4c663711`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dea99582140f80243d2a0ac703d7a5d9e0796d3fa513893a3439bd298b7da534`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `0aaaaa6132ac199ab12cdc680f91f6ae4c663711`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `dea99582140f80243d2a0ac703d7a5d9e0796d3fa513893a3439bd298b7da534`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
