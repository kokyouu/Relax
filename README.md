# Task 1: FULL checkpoint validation evidence

Sanitized evidence for the first format/storage and FULL integration PR related
to redai-studio/Relax#410. This branch contains review artifacts only.

- Source commit: `55dbc5de2e5dcc6cb4b27d57df14eb3761323f9d`
- Upstream base: `c9aff0effa5c50e8737539c70e1d7d406c4d9576`
- Source patch SHA256: `86e3d53833e31a2a0eaf73393777adf7bc7bea5420afe0d1592a9e908a224614`
- Validation date: 2026-11-06, Asia/Shanghai
- Archive SHA256: `3d4835839839c5cf69ec3760cc4599ab5280946aba3f025e4ac439e6cf7f2565`
- Archive size: 291021 bytes; 92 files

The archive includes results, successful-run logs, CPU JUnit, six-version
manifests/metrics, environment metadata, provenance and reproduction instructions.
Private workspace paths, intranet addresses and JUnit hostnames are redacted.
Source identities and numerical results are preserved. Verify the archive's
SHA256SUMS.json after extraction.

All 227 selected CPU tests and 11 subtests passed with zero skips. All pre-commit
hooks passed. Direct, Bridge and native Qwen3-VL completed TP2 export across five
optimizer updates and six FULL versions, HF reconstruction/comparison, and
independent SGLang loading/generation.

These are small randomly initialized correctness fixtures with synthetic
tokenizers. They do not establish production Qwen3-VL-4B acceptance, full M0,
language quality, full-repository pytest, online incremental synchronization,
multi-node/heterogeneous acceptance or final performance targets.
