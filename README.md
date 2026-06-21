# GBA-GCs Controlled Access Documentation

This repository documents the controlled-access path for non-public components of the GBA-GCs dataset associated with the ECCV 2026 paper:

**Urban Boundaries, Social Barriers: A Benchmark and Vision-Centric Framework for Mapping Gated Communities and Equity Implications**.

The raw archives are **not** hosted in this repository. This repository contains only:

- access policy
- data-use agreement template
- request form template
- manifest and checksums
- permitted-use and prohibited-use rules
- safe example schemas

Controlled components include AOI geometries, community names or provider identifiers when present, raw image chips, and provider-derived metadata. These files are distributed only after request review and signature of a non-commercial data-use agreement.

## Repository Contents

- `docs/ACCESS_POLICY.md`: who may request access and how requests are reviewed.
- `docs/CONTROLLED_RELEASE_POLICY.md`: ethics, redistribution, storage, and publication rules.
- `docs/DUA_TEMPLATE.md`: controlled data-use agreement template.
- `docs/SECURITY_AND_STORAGE.md`: minimum handling requirements for approved users.
- `forms/ACCESS_REQUEST_FORM.md`: information requesters should provide.
- `metadata/full_archive_manifest.csv`: archive inventory and SHA-256 checksums.
- `metadata/checksums_sha256.txt`: checksum list for approved archive verification.
- `metadata/guangzhou_human_label_manifest.csv`: Guangzhou human-label inventory.
- `metadata/manifest.json`: count summary and access level.
- `examples/controlled_manifest_schema.csv`: example schema, no raw data.
- `examples/approved_use_cases.md`: examples of permitted and prohibited uses.

## Public Dataset

The unrestricted anonymized release is hosted separately:

https://github.com/MinweiZhao/GBA-GCs

## Public Model Checkpoint

The MCGC checkpoint is distributed through the public repository's GitHub Releases, not through this controlled-access documentation repository:

- Release: https://github.com/MinweiZhao/GBA-GCs/releases/tag/v2026-06-mcgc
- Asset: `mcgc_trimodal_io_fused_gba_full.pth`
- SHA-256: `48518dafd9b2e2702db812ae9977bc6699bbc2e55c4a8044bd7d993114ebb1b8`

Controlled raw data access remains subject to DUA review. The public checkpoint does not grant permission to redistribute AOI polygons, names, provider identifiers, raw image chips, or provider-derived metadata.

## Access Principle

The project supports reproducible non-commercial research while minimizing risks of residential targeting, surveillance, re-identification, and violation of third-party data terms. Approved users may analyze controlled files only under the DUA and may publish only aggregate, privacy-preserving outputs.
