# Kestrel

A paper-trading demo of a perpetual futures exchange: one static page, no build step, no wallet.

- Original kestrel logo: nav mark flaps on hover and opens a live info card; large interactive emblem where each part of the bird explains part of the engine with live numbers
- Original illustrated emblem for every coin and pixel avatars for traders, all generated in-page
- Coin detail panel (chart, open interest, funding, copyable address), watchlist with stars, leaderboard with 24H/7D/30D
- Hero with live "deepest pools" board, token-address checker and a scrolling feed of demo fills
- Stats strip, small-cap market cards (sortable, load more), six pricing safeguards
- Interactive skew-pricing chart with market picker and two sliders
- ⌘K market search, paper-wallet Connect, simulated block / ETH / NYSE status
- Paper-trading terminal: chart with crosshair, long/short ticket with leverage capped by pool depth, premium, liquidation price and fees
- Open positions with live PnL, close, and automatic liquidation

- Vault yield estimator and FAQ

Open `index.html` in a browser. Demo state is saved in `localStorage`.

Licensed under MIT (see `LICENSE`).
