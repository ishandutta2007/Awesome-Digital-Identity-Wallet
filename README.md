# Awesome-Digital-Identity-Wallet

# Top Digital Identity Wallet Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Verifiable Credentials, SSI Wallets, mDL, OID4VCI/OID4VP & Decentralized Identity*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Identity Wallets**. These systems hold verifiable credentials (VCs), mobile driving licenses (mDL), and other attestations so users can prove identity attributes without oversharing.

**Examples** include Dock Labs, Affinidi, Validated ID, Trinsic, Spruce ID, Yoti Wallet, IDEMIA Wallet, Microsoft Entra Verified ID, OneSpan Identity Wallet, and Lissi (the category leaders).

**Open-source emphasis**: Digital identity wallets have a rich open stack. **Credo (Aries)**, **walt.id**, **Veramo**, **Spruce SSI**, **Bifold**, and OpenWallet Foundation projects enable standards-based wallets. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Microsoft Entra Verified ID, Trinsic, Affinidi, Dock](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-verified-id)**  
  Enterprise and developer platforms for issuing and verifying verifiable credentials at scale.

- **[Spruce ID, Validated ID, Lissi](https://spruceid.com/)**  
  SSI and European digital identity wallet specialists aligned with eIDAS and open standards.

- **[Yoti, IDEMIA, OneSpan](https://www.yoti.com/)**  
  Consumer and high-assurance identity wallet and verification providers.

- **[Other commercial digital identity wallet platforms](https://trinsic.id/)**  
  Additional OID4VC and mDL wallet offerings for governments and enterprises.

## Open-Source GitHub Projects

- **[Credo (OpenWallet Foundation / Aries)](https://github.com/openwallet-foundation/credo-ts)**  
  Leading open TypeScript framework for decentralized identity and verifiable credentials—successor path from Hyperledger Aries JS.

- **[Bifold Wallet](https://github.com/openwallet-foundation/bifold-wallet)**  
  Open React Native digital wallet reference app—extensible holder wallet built on Credo.

- **[walt.id](https://github.com/walt-id/waltid-identity)**  
  Open-source identity and wallet toolkit—issuer, verifier, and wallet APIs multi-platform.

- **[Veramo](https://github.com/decentralized-identity/veramo)**  
  Open JavaScript framework for verifiable data—DID agents, credentials, and key management.

- **[Spruce SSI libraries](https://github.com/spruceid/ssi)**  
  Open Rust core libraries for decentralized identity, VCs, and related protocols (SpruceID).

- **[ACA-Py (Aries Cloud Agent Python)](https://github.com/openwallet-foundation)**  
  Open Python agent widely used for issuer/verifier services in Aries-based ecosystems.

- **[Universal Resolver & DID methods](https://github.com/decentralized-identity/universal-resolver)**  
  Open DID resolution infrastructure from the Decentralized Identity Foundation.

- **[mDL / ISO 18013 open implementations](https://github.com/spruceid/isomdl)**  
  Open libraries for mobile driving license standards used in modern identity wallets.

### Additional Strong Open-Source Options

- **Holder wallet**: Bifold or walt.id white-label apps.
- **Agent framework**: Credo (TS) or ACA-Py (Python).
- **Issuer/verifier APIs**: walt.id or Veramo agents.
- **Composable stacks**: DID method + Credo/walt.id + OID4VCI/OID4VP + mobile wallet UI.
- Commercial platforms still lead in certified eIDAS wallets, enterprise support, and national-scale deployments.

**Frameworks for building custom systems**:  
**Credo** + **Bifold** for Aries-style wallets; **walt.id** or **Veramo** for flexible issuer/verifier/wallet stacks; **Spruce** libraries for Rust-centric builds.  
Commercial products (Entra Verified ID, Trinsic, Affinidi, Yoti, IDEMIA, etc.) provide managed cloud and compliance packaging.  
Many pilots and EUDI-related projects run on open components. Fully open digital identity wallets are production-capable when standards (W3C VC, OID4VC, mDL) are followed carefully.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity wallets hold high-value credentials. Protect keys (preferably hardware-backed), minimize data disclosure, and comply with eIDAS, GDPR, and local digital-ID law. Interoperability requires careful protocol and trust-list configuration.
- Open-source stacks offer transparency and portability but place security and certification effort on the implementer. Commercial platforms shift product and often compliance packaging to the vendor. Neither replaces proper trust frameworks and auditor review for high-assurance use.

---

**Made for identity architects, government digital-ID teams, and SSI builders.**  
Let's expand open, standards-based digital wallets while recognizing the assurance and scale that leading commercial identity platforms deliver.
