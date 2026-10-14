# Educators — OPENESTATE_PHP_EXPORT

**Project:** OPENESTATE_PHP_EXPORT  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/OpenEstate/OpenEstate-PHP-Export  
**Pinned commit:** `0aaaaa6132ac199ab12cdc680f91f6ae4c663711`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dea99582140f80243d2a0ac703d7a5d9e0796d3fa513893a3439bd298b7da534`  
**Date:** October 2026

## Teaching with OPENESTATE_PHP_EXPORT

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `dea99582140f80243d2a0ac703d7a5d9e0796d3fa513893a3439bd298b7da534` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
