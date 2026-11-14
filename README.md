# Open Policy Agent (OPA) — TrillionAI Engineering Reference

**Public source-code research archive only.** This is not a deployed Open Policy Agent service and does not authorise modifications to proprietary TrillionAI production systems.

## Original source provenance
- Official upstream: https://github.com/open-policy-agent/opa
- Pinned source commit: `8d10da6e34b846269f990daa43f39003e79b9dc4`
- Original source Git tree: `0d0c805a243292f6d2a57a9cf6bf5688b8dd7483`
- Original tracked inventory: 9,212 Git tree entries including 8,049 file blobs (75,855,051 bytes of tracked blob content).
- Upstream root licence: **Apache License 2.0**. The original upstream `LICENSE` and other notices must remain intact.
- Destination layout: original tracked source **directly on `main`**, with original upstream `README.md` and its directory structure.
- Current status: **PENDING SOURCE IMPORT**; only mark verified after remote Git tree verification and a source-file read.

## Research purpose

Study real policy-as-code and decision-engineering components for TrillionAI Audit, including:
1. Rego policy syntax, evaluation and policy-result provenance.
2. Tenant-scoped policy versions, immutable evaluation inputs and deterministic results.
3. AppForge release decisions based on verified evidence rather than fictional test success.
4. Policy testing, sandboxing, permission boundaries, budgets and error handling.
5. Clear `allow`, `deny`, `not assessed` and `not applicable` evidence for customer reports.

## Import and source-integrity contract

The import workflow fetches **exactly the pinned upstream Git commit and tree**, retains the original tracked source on `main`, moves this research document into `TRILLIONAI_REFERENCE.md` and removes the imported original `.github/workflows/` definitions to prevent unintended third-party CI execution. It compares Git object hashes and file modes for all other upstream files, then verifies the remote `main` tree.

The root destination Git tree will therefore differ from the original upstream tree **only** in the intentional GitHub workflow omission and the added research note. It is not a full-history Git mirror, downloaded dependency set, runnable OPA installation or passing test suite.

If GitHub push protection rejects any credential-like upstream fixture, do **not** bypass it; document any necessary source exclusion and verify the filtered source separately.

## Licensing and product boundaries

OPA remains copyrighted by the original authors/contributors under its applicable source and component licences. This repository does **not** relicense upstream code. Build original TrillionAI Node.js/TypeScript policy adapters and Flutter interfaces in their own repositories; assess licence obligations before reusing actual upstream source. No paid services or production workloads are activated by this archive.
