# Koi-Koi — Online Hanafuda

A two-player Hanafuda card game (Koi-Koi rules), playable online with a friend on separate devices, or pass-and-play together on one. Built as a single self-contained HTML file — no server, no build step, no install.

## How to play

Open the hosted page, then either:
- **Host a game** — share the generated room code with a friend so they can join from their own device, or
- **Play Pass-and-Play** — share one device and pass it back and forth each turn.

Before starting, choose the number of rounds (3/6/9/12) and a Koi-Koi mode (Unlimited, capped at 1 or 3 calls per round, or disabled entirely for auto-Shobu).

## Features

- **Full yaku scoring**, including Goko/Shiko/Ame-Shiko/Sanko brights, Ino-Shika-Cho, Tsukimi-zake, Hanami-zake, Tane, Tanzaku, Akatan/Aotan (with combined Chofuku), and Kasu.
- **Teyaku instant-win hands** — Teshi and Kuttsuki are detected automatically on the opening deal.
- **Standard Koi-Koi scoring bonuses**: calling Koi-Koi at all during a round doubles the final score once, and a yaku worth 7+ points doubles it again — capped at a combined 4x, regardless of how many times Koi-Koi was called.
- **Both-players-ready round advancement** — the next round only starts once both seats have confirmed on the round-end screen, whether playing online or pass-and-play.
- **🧮 Yaku Scoring Simulator** — a standalone mode from the lobby where you can tap any cards from the full deck to mark them "captured" and see the resulting score, complete with a Koi-Koi call counter and card thumbnails showing exactly which cards earned each yaku. Great for double-checking scores in a physical game.
- **📖 Yaku & Deck Guide** — a toggleable reference showing every yaku and the full 48-card deck, with its Close button anchored to the top of the popup so it's always reachable.
- **Resume in progress** — game state is saved automatically, so a refreshed or reopened tab can pick a game back up.
- **Light/dark theme toggle.**

## Credits

Built with **[Claude AI](https://claude.ai)** (Anthropic).

Card artwork by **[jcanabal](https://jcanabal.itch.io/hanafuda-deck-pixel-art)** (itch.io).
The artwork is licensed for use **within this game only** — please don't extract, redistribute, or reuse the image files elsewhere. If you'd like to use jcanabal's Hanafuda deck for your own project, please get it directly from their itch.io page linked above.

Networking powered by [PeerJS](https://peerjs.com/) (peer-to-peer, no game server).

## License

The game code in this repository is provided as-is for personal use. The card artwork is © jcanabal and used under its original license terms — it is **not** covered by any license you may apply to the code itself.
