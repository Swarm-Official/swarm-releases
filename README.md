# SWARM testnet — downloads

Verified, **unsigned test builds** of the SWARM testnet apps. **Test coins only: SWM on SwarmTestnet has no value and the chain may be reset.**

Every release lists the file's SHA-256 in `SHA256SUMS` and the exact source commit and CI run in `release-manifest.json`. Verify before you run:

    sha256sum -c SHA256SUMS

Windows SmartScreen and Android Play Protect will warn about unsigned apps: choose "More info → Run anyway" / "Install anyway". Nobody from the project will ever ask you for recovery words, private keys or a payment.

Official channels, and nothing else speaks for the project: https://swarm.green · https://github.com/brs-holding · X @swarm_coin · swarmofficial@atomicmail.io

## Source code

Everything SWARM runs is open source. The chain reuses Zcash's software with **no change to consensus or cryptography**; each fork carries only configuration, branding and build changes, documented in `docs/AUDIT-2026-09-22.md` of the project.

| Component | Repository | Based on |
| --- | --- | --- |
| Node (consensus, mining) | https://github.com/Swarm-Official/privacy-zebra | Zebra 6.3.0 by the Zcash Foundation |
| Wallet server (indexer) | https://github.com/Swarm-Official/privacy-zaino | Zaino by ZingoLabs |
| Wallet SDK | https://github.com/Swarm-Official/privacy-zingolib | zingolib by ZingoLabs |
| Desktop wallet | https://github.com/Swarm-Official/privacy-wallet | Zingo PC by ZingoLabs |
| Mobile wallet (Android, iOS) | https://github.com/Swarm-Official/swarm-mobile | Zingo Mobile by ZingoLabs |
| Block explorer | https://github.com/Swarm-Official/swarm-explorer | zcash-explorer (Nighthawk lineage) |
| Server stack | https://github.com/Swarm-Official/privacy-z3 | Z3 |
| Downloads (this repository) | https://github.com/Swarm-Official/swarm-releases | — |

The mining app SWARM Node and the website live in the same organisation (https://github.com/Swarm-Official); their source repositories open with the public hive.
