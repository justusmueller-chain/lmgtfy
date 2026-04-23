# 🔍 Let Me Glean That For You

> For all those questions that could've been a Glean search.

The spiritual successor to [Let Me Google That For You](https://letmegooglethat.com/), built for teams that use [Glean](https://www.glean.com/).

## How it works

1. Someone asks you a question they could've easily searched for
2. You type their question into LMGTFY and get a link
3. You send them the link with a straight face
4. They watch a mouse cursor click the search bar, type out their question, get lovingly roasted, and then get redirected to the actual Glean results

## Demo

**Create a link:** [justusmueller-chain.github.io/lmgtfy](https://justusmueller-chain.github.io/lmgtfy/)

**Example playback:** [justusmueller-chain.github.io/lmgtfy/?q=how do I reset my password](https://justusmueller-chain.github.io/lmgtfy/?q=how%20do%20I%20reset%20my%20password)

## Setup

It's a single HTML file. No build step, no dependencies, no framework, no node_modules.

1. Fork or clone this repo
2. Enable GitHub Pages (Settings → Pages → Deploy from `main` branch)
3. That's it. Go spread the love.

## Customization

If your Glean instance uses a different backend URL, update these two lines near the top of `index.html`:

```js
const GLEAN_BASE_URL = 'https://app.glean.com/';
const GLEAN_BE = 'https://chainalysis-prod-be.glean.com';
```

## License

MIT — do whatever you want with it. Passive-aggressiveness is free.
