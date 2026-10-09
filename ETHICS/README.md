# Ethics — OPENESTATE_PHP_EXPORT

**Project:** OPENESTATE_PHP_EXPORT  
**Category:** REAL_ESTATE  
**Upstream:** https://github.com/OpenEstate/OpenEstate-PHP-Export  
**Pinned commit:** `0aaaaa6132ac199ab12cdc680f91f6ae4c663711`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `dea99582140f80243d2a0ac703d7a5d9e0796d3fa513893a3439bd298b7da534`  
**Date:** October 2026

## Position

OPENESTATE_PHP_EXPORT is packaged for offline deployment with a verifiable audit trail. The
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
