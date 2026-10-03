# Kestrel

A paper-trading demo of a perpetual futures exchange: one static page, no build step, no wallet.

- Live simulated price tape, chart with crosshair, and timeframe toggle
- Order ticket with long/short, leverage capped by each market's pool depth, price impact, liquidation price and fees
- Open positions with live PnL, close, and automatic liquidation
- Sortable, searchable market board (click a row to trade it)
- Vault yield estimator and FAQ

Open `index.html` in a browser. Demo state is saved in `localStorage`.

Licensed under MIT (see `LICENSE`).
