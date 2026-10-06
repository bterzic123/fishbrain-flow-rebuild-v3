# Search to Pro · Fishbrain (Growth Audit volume 3: Apple Ads keyword flows)

The five ranked ideas from volume 2, plus two versions of Fishbrain's onboarding and paywall side by side: one for people who searched "free fishing app" on the App Store, one for people who searched "bass fishing app".

**→ https://bterzic123.github.io/fishbrain-flow-rebuild-v3/**

Public, no login. Opens on the Overview. Add `?open=proto` to land on the prototype, and `&step=paywall` (or `search`, `welcome`, `interests`, `species`, `loader`, `payoff`, `offer`, `done`) to open both phones on one screen.

Volume 2: https://bterzic123.github.io/fishbrain-flow-rebuild-v2/ · Volume 1: https://bterzic123.github.io/fishbrain-flow-rebuild/ · Apple Ads research: https://asa.adapty.io/fishbrain

## What is new in volume 3

- **Overview:** an Apple Ads block that links to the Fishbrain Apple Ads research and to the two flows.
- **Prototype:** two phones driven by one step bar. Tap through either phone and the other follows.
- **App Store search screen** at the start of each flow: the Fishbrain ad as it would appear for that keyword.
- **Ideas panel:** the five audit ideas are built into both flows. For each step the panel shows what differs between the two keywords, with a potential outcome for each.
- **30-second walkthrough** plays both flows at once.
- EN / SV / ES, Light / Dark. On a phone, a toggle switches between the two flows.

## What differs by keyword

| Screen | "free fishing app" | "bass fishing app" |
| :-- | :-- | :-- |
| App Store | Screenshots say "Start free" | Screenshots show a bass, lures, bass catches |
| Welcome | "Free to start" · Start free | "Catch more bass" · Find bass near me |
| Species | Unchanged | Bass first, Largemouth already picked |
| Your water | What stays free vs what Pro opens | Every line about bass |
| Paywall | 7-day trial on by default, US$0.22 a day | Carousel rewritten for bass, 3-day trial |
| Offer on close | Keep using Fishbrain free, or monthly | Free vs Pro table led by bass features |

The 7-day trial is a hypothesis: Fishbrain sells a 3-day trial today, so it needs a new product in App Store Connect.

## Grounding

Every price, rating, quote and feature line comes from Fishbrain's own published material: the US App Store listing, fishbrain.com, fishbrain.com/pro and Fishbrain's in-app screens. Apple Ads figures come from Adapty's Fishbrain research. Impact ranges are Adapty's expected effect from tests across subscription apps, not measured lift for Fishbrain.

## Run it locally

```bash
git clone https://github.com/bterzic123/fishbrain-flow-rebuild-v3.git
cd fishbrain-flow-rebuild-v3 && python3 -m http.server 8000
```

Then open http://localhost:8000. No build step and no dependencies.
