# SpaceCat ($SPACECAT)

Space-style meme landing page for the Robinhood / cosmic cat narrative.

## Contents
- `index.html` — site
- `styles.css` — space theme
- `config.js` — **edit CA + DexScreener pair here**
- `assets/` — logo, banner, Hubble video BG, tweet media

## Local preview
```bash
cd robinhood-meme-site
python3 -m http.server 8777
```
Open http://127.0.0.1:8777/

## Wire live CA
Edit `config.js`:
```js
ca: "YOUR_CONTRACT_ADDRESS",
dexscreenerPair: "solana/YOUR_PAIR_OR_TOKEN", // or base/... ethereum/... etc.
```

## Sources
- Hubert call: https://x.com/HubertTradez/status/2116186447413903410
- NASA Hubble video: https://x.com/NASAHubble/status/2116183343444140287
