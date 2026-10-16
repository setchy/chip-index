# 🍟 Chip Index

[![Status][status-badge]][website] [![Website][website-badge]][website]

> Rate the crunch. Share the obsession.

![Chip Index][social]

Chip Index is the world's first social platform built for chip lovers — think
[Untappd][untappd], but for potato chips, hot chips, fries, wedges and every
starch-based snack on the planet.

Check in wherever you are, log what you're eating, score it on the dimensions
that actually matter, and share the obsession with friends around the globe.
Whatever you call them — *crisps*, *chips*, *frites*, *patatine* — every bite
has a score.

---

## ✨ Features

- 📍 **Check in anywhere** — log the snack, the place and the moment it happened
- 🧮 **Seven-dimension scoring** — hotness, sauce, seasoning, crunch, value,
  repeatability and drinkability
- 🍟 **Every kind of crunch** — potato chips, hot chips, fries, wedges, gems,
  scallops, curls, sticks and wafers
- 🌍 **Every dialect** — from *crisps* to *patatine*, if it crunches, it counts
- 👯 **Share the obsession** — ratings, reviews and recommendations from friends
- 🗺️ **Discover hidden gems** — find the best chips wherever you travel, and the
  ones to skip
- 📖 **Snack adventure history** — every bite you've ever logged, in one place

## 🧂 The score

Every chip is rated on the dimensions that actually matter:

| Dimension              | What it measures                                      |
| ---------------------- | ----------------------------------------------------- |
| 🌶️ **Hotness**         | Heat level — from mild to nuclear                     |
| 🫙 **Sauce**           | Dipping sauce or flavour sauce quality                |
| 🧂 **Seasoning**       | Flavour depth and accuracy                            |
| ✨ **Crunch Factor**   | The sound. The resistance. The satisfaction.          |
| 💰 **Value for Money** | Chip-to-price ratio — hidden gems vs. highway robbery |
| 🔁 **Repeatability**   | Would you buy this again? The true overall signal     |
| 🍺 **Drinkability**    | How well it pairs with your drink of choice           |

## 🌏 One snack, many names

Chip Index meets every chip where it lives:

| Region              | Known as                                        |
| ------------------- | ----------------------------------------------- |
| 🇺🇸 United States  | potato chips, curly fries                       |
| 🇬🇧 United Kingdom | crisps                                          |
| 🇦🇺 Australia      | hot chips, wedges, potato gems, potato scallops |
| 🇫🇷 France         | frites                                          |
| 🇮🇹 Italy          | patatine                                        |
| 🇪🇸 Spain          | papas fritas                                    |
| 🇯🇵 Japan          | ポテチ                                          |
| 🇮🇳 India          | wafers                                          |

## 🚀 Status

> [!NOTE]
> **Frying soon** — Chip Index is still in the fryer. Follow along at
> [chips.setchy.io][website].

Want early access? [Get in touch][contact] and we'll save you a seat at the
table.

## 🛠️ Build & Development

Chip Index is a single static [`index.html`](index.html) — no build step, no
dependencies. Clone it and serve the repo root:

```shell
git clone https://github.com/setchy/chip-index.git
cd chip-index
python3 -m http.server 8000
```

Then open <http://localhost:8000>. The site deploys with GitHub Pages and is
served at [chips.setchy.io][website] via [`CNAME`](CNAME).

## 📬 Community & Support

- Open an [issue][github-issues] for bugs or feature requests
- Say hello at [setchy.io][contact] for early access

---

© Chip Index — [chips.setchy.io][website]

<!-- LINK LABELS -->

[social]: assets/social.png
[website]: https://chips.setchy.io
[contact]: https://setchy.io
[untappd]: https://untappd.com

[github]: https://github.com/setchy/chip-index
[github-issues]: https://github.com/setchy/chip-index/issues
[renovate]: https://github.com/setchy/chip-index/blob/main/renovate.json

[status-badge]: https://img.shields.io/badge/status-frying%20soon-orange
[website-badge]: https://img.shields.io/website?url=https%3A%2F%2Fchips.setchy.io&logo=githubpages&logoColor=white