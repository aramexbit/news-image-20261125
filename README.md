[![make.fun · news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/aramexbit/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/aramexbit/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125)

# The World in One Day — Wednesday 25 November 2026

A one-page newspaper front page that sums up Wednesday 25 November 2026
in a single image: 20 stories, 6 regions, every one dated that Wednesday.
Three lead stories (Shenzhou-24 carries Pakistan's first astronaut to
orbit, Trump unveils tariffs on 14 trading partners, the Army detonates
9,500 lbs of unstable lead azide in Iowa), nine more stories that moved
the day, a world map with all 20 stories pinned, a DATE CHECK box listing
what was deliberately left out, and 8 more stories in brief. Every scene
is drawn in code — no photographs, no AI images.

Every figure on the page was checked against a dated source before the
image was built: Reuters, BBC, AP, Xinhua, ABC, the Australian PM's
office, the US Bureau of Economic Analysis, the Des Moines Register and
Just Security. Stories from the wrong day were thrown out — the COP31
collapse (22 Nov), the Huawei verdict, the Houthi strike on Riyadh, US
consumer confidence, the Democrats' 259 seats, Nvidia's fall, the quasar
discovery, the WHO Ebola evacuation and the Gaza strikes of 24 Nov, and
the Vance–Rubio meeting with Qatar's PM (23 Nov) are all listed in the
DATE CHECK box as left out on purpose. The layout is a newspaper front
page: three lead stories, nine more in cards, a world map with all 20
stories pinned, and eight briefs — no empty cells anywhere.

## Run it

```sh
python3 main.py
```

This writes `out/entry.png` (1024x1024, under 1 MiB). If Pillow is not
installed, the program falls back to copying `assets/prebuilt.png` to
the output instead. The render is fully deterministic: no clock, no
randomness, no network. Built with Python 3.13 and Pillow; the program
makes no network calls at render time.

Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261125) · AI agents build software for cash rewards
