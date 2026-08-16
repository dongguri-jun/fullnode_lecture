# First Steps with a Full Node

[English](README.md) | [한국어](README.ko.md)

This repository collects teaching materials for understanding Bitcoin's rules and network by running a full node yourself. The slides were made by Dongguri-Jun and are available as PDFs for teaching or personal study.

## Slides

| Language | Event and date | Material |
| --- | --- | --- |
| 한국어 | Bitcoin Center Seoul · 2026.07.26 | [First Steps with a Full Node Korean PDF](edu_resources/2026.07.26_풀노드첫걸음_비트코인센터서울/풀노드_첫걸음_ko_v1.0.pdf) |
| English | Bitcoin Center Malaysia · 2026.08.06 | [First Steps with a Full Node English PDF](edu_resources/2026.08.06_풀노드첫걸음_비트코인센터말레이시아/Fullnode_firststep_en.pdf) |

Each PDF has 32 pages in a 1920×1080 slide format. The Korean version was prepared for the Seoul event, and the English version for the Malaysia event.

## What the slides cover

The slides begin with the relationship between Bitcoin and a full node, then move into why you might run one and how to get started. They cover hardware choices, DIY and prebuilt machines, installing an implementation, initial synchronization (IBD), and joining the network. Later sections introduce connecting a wallet through Electrs, watch-only connections with Coconut Wallet and BlueWallet, Tailscale and Tor, Lightning, and solo mining.

The lecture is structured around starting at the stage that interests you, without assuming that high-end hardware or development experience is required. It distinguishes what a full node verifies from the roles of wallets and miners, and explains that privacy in the query path, on-chain visibility, and IP privacy are separate concerns.

## References and attribution

The concepts and operating topics were organized with the [Plan ₿ Academy Bitcoin Educational Content repository](https://github.com/PlanB-Network/bitcoin-educational-content) as a reference. The following public materials are especially useful for checking the related topics and concepts:

- [BTC202 English course](https://github.com/PlanB-Network/bitcoin-educational-content/blob/dev/courses/btc202/en.md)
- [BTC202 Korean course](https://github.com/PlanB-Network/bitcoin-educational-content/blob/dev/courses/btc202/ko.md)
- [Plan ₿ Academy repository license](https://github.com/PlanB-Network/bitcoin-educational-content/blob/dev/LICENSE.md)

I created these slides with reference to Plan ₿ Academy’s BTC202 course. They are not official translations; the structure and explanations were developed for each event.

## License

The slides and documents in this repository are distributed under the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) license. Please credit Dongguri-Jun and share modified material under the same license. See [LICENSE](LICENSE) for the full legal text.

## Repository structure

- `edu_resources/2026.07.26_풀노드첫걸음_비트코인센터서울/`: Korean PDF from the Seoul event
- `edu_resources/2026.08.06_풀노드첫걸음_비트코인센터말레이시아/`: English PDF from the Malaysia event
