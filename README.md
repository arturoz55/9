# Kestrel

A paper-trading demo of a perpetual futures exchange: one static page, no build step, no wallet.

- Hero with live "deepest pools" board, token-address checker and a scrolling feed of demo fills
- Stats strip, small-cap market cards (sortable, load more), six pricing safeguards
- Interactive skew-pricing chart with market picker and two sliders
- ⌘K market search, paper-wallet Connect, simulated block / ETH / NYSE status
- Paper-trading terminal: chart with crosshair, long/short ticket with leverage capped by pool depth, premium, liquidation price and fees
- Open positions with live PnL, close, and automatic liquidation

- Vault yield estimator and FAQ

Open `index.html` in a browser. Demo state is saved in `localStorage`.

Licensed under MIT (see `LICENSE`).
