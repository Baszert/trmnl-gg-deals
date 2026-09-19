# GG.Deals

Watch the prices of the games you want most. See what they cost now and how low they've been before, for retail and keyshops. At its all-time low, the price is shown in a black box.

<a href="https://trmnl.com/recipes/192524"><img width="150" alt="Works with TRMNL" src="https://trmnl.com/images/brand/badges/light/works-with-trmnl/trmnl-badge-works-with-light.svg" /></a>

## Settings
- **API key:** from your [GG.deals account](https://gg.deals)
- **Steam App IDs:** comma-separated, find them on [SteamDB](https://steamdb.info/) (up to 4 games)
- **Region:** price region

Full shows 4 games, half vertical 3, half horizontal 2 and quadrant 1. Each game gets a QR code to its GG.deals page. Data from the [GG.deals API](https://gg.deals/api/).

### Develop locally

Templates and settings live in [`src/`](src/), ready for [trmnlp](https://github.com/usetrmnl/trmnlp):

```sh
gem install trmnl_preview
trmnlp serve
```

Questions or ideas? trmnl@achtnegen.nl or @Bastronautica on Discord.
