# HEAL — Token Features & Controls (Policy)

**Immutables at issuance**
- Fixed supply: 100,000,000 HEAL
- Decimals: 6

**Feature flags**
- Enabled: burning, extension
- Disabled: minting, freezing, whitelisting, block-smart-contract, clawback
- Optional (DAO-later): IBC

**Operational rules**
- No freeze or clawback mechanics shall be introduced via extensions.
- Extensions must be minimal, modular, audited, and DAO-controlled.
- Any extension change uses a new Code ID; prior Code IDs remain available for rollback.
- No PII written on-chain; off-chain telemetry uses opaque IDs/CIDs only.
