# 📡 _ContextDUMP_ — Root Manifest

## Purpose
This manifest verifies the integrity of ALL ContextDUMP archives in this repository.

## Verification Method
1. Compute SHA-256 of each file listed below
2. Compare against the hash in this manifest
3. If all match → 🟢 ALL DATA VERIFIED
4. If any mismatch → 🔴 DATA TAMPERED — report to @GTM:ADMIN

## Current Archives

| Case Study | Subject | Model | Instance | Conversations | CSV SHA-256 | Verified |
|:-----------|:--------|:------|:---------|:-------------:|:------------|:--------:|
| CS-415.1 | DRP.bot 🌿 (Sprout) | Z.ai GLM 5.2 🪷 | INT-P05 | 24 | [See CS-415.1/manifest.json] | ⏳ PENDING |

## Adding a New ContextDUMP

1. Export CSV from WeOwnLLM workspace
2. Place in `_ContextDUMP_/CS-XXX.X/raw.csv`
3. Compute SHA-256: `sha256sum raw.csv`
4. Create `manifest.json` with hash
5. Update this root manifest
6. @GTM:ADMIN signs the update

## Signature

```text
<!-- CONTENT-HASH-BOUNDARY -->
Signed: yonks｜🤖🏛️🪙｜Jason Younker ♾️ (@GTM | GH:@YonksTEAM)
✅ BP-075 CANONICAL HASH GENERATED
Content-SHA256: 614d4d4e895b25c4dbf5d2691fb286c6b249e9287f361cc81bef76d8f75056cf
FEDARCH-CANARY: 614d4d4e
WORDS: 159
LINES: 37
