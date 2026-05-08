# Security Build Notes

This document provides required supply-chain guardrails for builds and releases.

| Area | Required control |
|---|---|
| Source archives | SHA-256 checked |
| Toolchains | Version pinned where practical |
| Homebrew installs | Accepted risk documented |
| Release binaries | Built only from protected refs |
| Secrets | Not available to untrusted PR paths |
| Artifacts | Named, checked, and attached only after tests |
