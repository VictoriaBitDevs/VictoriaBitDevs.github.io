---
layout: post
type: socratic
title: "Socratic Seminar 1"
meetup: https://www.meetup.com/vicbtc/events/291012377
---


## Announcements
Please join us for our inaugral Socratic Seminar in the city of Victoria. Please make sure you are RSVP'd, an identifier (but not a full name) is required for entry.

As a reminder, the ground rules of BitDevs are as follows:
1. No photos, videos, or recordings
2. [Chatham House Rule](https://en.wikipedia.org/wiki/Chatham_House_Rule): you may reiterate the contents of the meeting without attribution

These rules exist so that BitDevs participants can speak freely within the event

## Mailing Lists, Meetings and Bitcoin Optech

### Mailing Lists

#### bitcoin-dev

- [Opt-in full-RBF - Zero-conf apps in immediate danger](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-December/021226.html), [one response](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-December/021242.html)
- [Package Relay Proposal](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-November/021140.html)

#### lightning-dev

- [Channel Jamming countermeasures](https://research.chaincode.com/2022/11/15/unjamming-lightning/)
- [Mitigating Channel Jamming with Reputation Credentials: a Protocol Sketch](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-November/003754.html), [proposal summary](https://github.com/lightning/bolts/blob/aa8ac0ebb38040c193a5f67d2ef8b4ffc909fb76/history/www-reputation-credentials-protocol.md)
- [Mitigating Channel Jamming with Upfront fee](https://github.com/lightning/bolts/pull/1052), [proposal summary](https://github.com/lightning/bolts/blob/dc31129b1e6edd0706e891da94c437b126c5ab35/proposals/channel-jamming-mitigation.md)

### Meetings

- Bitcoin PR Review Club
    - [26631 add coverage for dust mempool policy (-dustrelayfee setting) (tests)](https://bitcoincore.reviews/26631)
- Bitcoin Core general developer meetings
	- [January 19th](https://www.erisian.com.au/bitcoin-core-dev/log-2023-01-19.html)
- Lightning Specification meeting
    - [January 16th](https://github.com/lightning/bolts/issues/1050)

### Optech

- [Newsletter #231 - 2022 Year-in-Review](https://bitcoinops.org/en/newsletters/2022/12/21/), [audio recap](https://twitter.com/bitcoinoptech/status/1605941173452824576)
- [Newsletter #233](https://bitcoinops.org/en/newsletters/2023/01/11/), [audio recap](https://twitter.com/bitcoinoptech/status/1613551393628995584)
- [Newsletter #234](https://bitcoinops.org/en/newsletters/2023/01/18/), [audio recap](https://twitter.com/bitcoinoptech/status/1616087744077508613)

## Network Data

- [Bitcoin Mining Map](https://ccaf.io/cbeci/mining_map)
- [monitor fullrbf replacements](https://fullrbf.mempool.observer/)
- [top fee-earning lightning routing nodes 2022](https://mobile.twitter.com/alexbosworth/status/1601243139347730437)

### Research

- [Bitcoin Security-Latency Under Network Delay](https://arxiv.org/abs/2212.01372v1)
- [(Concurrently Secure) Blind Schnorr from Schnorr](https://eprint.iacr.org/2022/1676)
- [Do Not Rug on Me: Leveraging Machine Learning Techniques for Automated Scam Detection](https://www.mdpi.com/2227-7390/10/6/949)
- [Jolt: Recovering TLS Signing Keys via Rowhammer Faults](https://eprint.iacr.org/2022/1669)
- [Stateful Layered Chain Model to Improve the Scalability of Bitcoin](https://assets.researchsquare.com/files/rs-2249748/v1/4ce4be5b-1e2d-448c-ba33-d40df6ccc265.pdf?c=1668441157)
- [Stronger Security and Generic Constructions for Adaptor Signatures](https://eprint.iacr.org/2022/1687)
- [Threshold Signatures with Private Accountability](https://eprint.iacr.org/2022/1636)

### InfoSec

- [Luke lost his coins](https://twitter.com/LukeDashjr/status/1609613748364509184), [one postmortem](https://lordx64.medium.com/multiple-linux-backdoors-discovered-targeting-bitcoin-core-developer-technical-analysis-793f8491f561)
- [BinaryWatch.org](https://binarywatch.org/)

## Pull Requests and repo updates

### Bitcoin Core

- [rpc: Return fee and prevout (utxos) to getrawtransaction](https://github.com/bitcoin/bitcoin/pull/23319)
- [p2p: Erlay support signaling follow-up](https://github.com/bitcoin/bitcoin/pull/26359), [erlay pr](https://github.com/bitcoin/bitcoin/pull/21515)

### lnd

- [pathfinding: capacity-dependent apriori model probability](https://github.com/lightningnetwork/lnd/pull/6857)
- [kvdb: add sqlite](https://github.com/lightningnetwork/lnd/pull/7251)

### eclair

- [Improve htlc_maximum_msat in channel updates](https://github.com/ACINQ/eclair/pull/2299)
- [Create routes to self using remote alias](https://github.com/ACINQ/eclair/pull/2507)

### c-lightning

- [reckless, plugin manager](https://github.com/ElementsProject/lightning/pull/5647)
- [Offers: bolt12 updated for latest draft](https://github.com/ElementsProject/lightning/pull/5676)
- [Blinded paths cross-compatibility issues](https://github.com/ElementsProject/lightning/issues/5823)

## New Releases

- [Bitcoin Core v24.0.1](https://github.com/bitcoin/bitcoin/releases/tag/v24.0.1) - mempoolfullrbf, sendall rpc, new headers dl logic, more
- [Core Lightning v22.11](https://github.com/ElementsProject/lightning/releases/tag/v22.11) , [blog](https://github.com/ElementsProject/lightning/releases/tag/v22.11) - reckless plugin manager, splicing scaffolding, more
- [eclair v0.8.0](https://github.com/ACINQ/eclair/releases/tag/v0.8.0) - zero-conf channels, channel aliases, BOLT 12 scaffolding
- [libsecp256k1 v0.2.0](https://github.com/bitcoin-core/secp256k1/releases/tag/v0.2.0) - schnorrsig, extrakeys and ECDH made default
- [Phoenix v1.4.24](https://github.com/ACINQ/phoenix/releases/tag/android-legacy-v1.4.24) - LNURL-auth updates
- [specter-desktop v1.14.0](https://github.com/cryptoadvance/specter-desktop/releases/tag/v1.14.0) - taproot psbt fields
- [Tor Browser v12.0](https://blog.torproject.org/new-release-tor-browser-120/) - m1 support, https-only by default
- [RTL v13.4-beta](https://github.com/Ride-The-Lightning/RTL/releases/tag/v0.13.4) - 2FA Hotfix

## Events and Podcasts

- [OP_VAULT & Bitcoin Governance](https://tftc.io/tftc-podcast/388-op_vault-and-bitcoin-governance-james-obeirne/)
- [Solving Lightning Channel Jamming](https://podcast.chaincode.com/2022/11/23/clara-sergei-lightning-jamming.html)
- [SLP438 Lawrence Nahum - RBF, Green, Jade, BuildonL2](https://stephanlivera.com/episode/438/)
- [SLP447 K3tan 2022 Year in review](https://stephanlivera.com/episode/447/)

## Mining

- [B.C. pauses new electrical connections for mining](https://news.gov.bc.ca/releases/2022EMLI0067-001928)
- [Coinmetric's State of the Network’s Q4 2022 Mining Data Special](https://coinmetrics.substack.com/p/state-of-the-network-issue-185#new_tab)
- [How Does the Current Bitcoin Mining Bear Market Compare to Previous Ones?](https://hashrateindex.com/blog/how-does-the-current-bitcoin-mining-bear-market-compare-to-previous-ones/)

## Miscellaneous

- [Taro: A new asset issuance protocol on Bitcoin](https://coinshares.com/research/taro-a-new-asset-issuance-protocol-on-bitcoin#major_taro_opportunities)
- [Lightning Privacy Research](https://lightningprivacy.com/en/introduction)
- [Miner centralization debate rages on...](https://twitter.com/LynAldenContact/status/1607456776567525376)
- [NYDIG research on bitcoin development](https://assets-global.website-files.com/614e11536f66309636c98688/63208342664438223226c3de_NYDIG%20-%20Developers%20of%20Bitcoin%202022.pdf)
- [Nostr catches fire](https://nostr-resources.com)
- [Emerging markets powering lightning growth](https://lightninglabs.substack.com/p/signal-over-noise-how-emerging-markets)

## Beginner Learning Resources
- [The Beginner's Guide to Bitcoin podcast series](https://www.whatbitcoindid.com/the-beginners-guide-to-bitcoin)
- [Bitcoin Infographics](https://www.bitcoindesigned.com/)
- [Book recommendation - The Bullish case for Bitcoin](https://vijayboyapati.medium.com/the-bullish-case-for-bitcoin-6ecc8bdecc1)

## Meme of the day
- [Bitcoiners vs Gold Bugs](https://twitter.com/gregzaj1/status/1619015997876486151)