# HEAL Token — Whitepaper Appendix (Technical Specification)

## Visual Peg (Canonical)
- Background: **#0B3D91** (royal blue)
- Accent (ring + rays): **#F3F8FF** (diamond white)
- Rays: **straight bars** with a single rounded outer tip; **bases start at the inner circle radius**; **no gap across the ring**
- Geometry: **inner 144**, **outer 177**, **ring thickness 33**; **short total length 210**; **long total length 277**; **ray thickness 33**
- Canvas: **1024×1024**, **45° symmetry**, pure SVG vector

**Integrity (SHA‑256)**
- HEAL_FINAL_diamond_straight_solid.svg — `6ebb1f630bdc46a1384be3273657ff5860dde83d1b86ff876a4547d69bba4937`
- HEAL_FINAL_diamond_straight_transparent.svg — `f5e49ac14bf30d93f27ac971e91a6f2cb4632a87be49f45e4f063051e15acece`

## Token Parameters
- Name/Symbol: **HEAL**
- Total Supply: **100,000,000 HEAL** (fixed)
- Decimals: **6**
- **Enabled:** burning, extension
- **Disabled:** minting, freezing, whitelisting, block-smart-contract, clawback
- **Optional (DAO):** IBC

## Extension & Upgrades
- Code ID versioning: **incremental only** (`001`, `002`, …); no in-place reuse.
- Governance control: DAO binds/unbinds extension Code IDs via proposal.
- Rollback: rebind to prior Code ID by DAO vote.

## Governance (baseline parameters)
- Quorum: **20%** of voting power
- Vote period: **7 days**
- Execution delay: **24 hours**
- Optional: quadratic weighting for anti-whale guard

## Transparency Links
- Metadata JSON (off-chain/IPFS-ready): **HEAL_token_metadata_FINAL.json** — `7934e5a1e59fd06398ae75d2d74389a955709a89fa78fd89947e733983f768d5`
- Coreum issuance config (conceptual): **HEAL_coreum_token_config_FINAL.yaml** — `78ed05d7f6552e85928219bb90bf57bb490ec623d3bec99a3e9731abd4f34cb8`

