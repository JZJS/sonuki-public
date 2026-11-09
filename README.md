<p align="center">
  <img src="public/sonuki.png" alt="Sonuki mascot" width="150">
</p>

<h1 align="center">Sonuki</h1>

<p align="center"><strong>Swap tokens, run perp strategies, and build your portfolio on SoDEX.</strong></p>

Sonuki is a trading and portfolio interface for SoDEX. Its three tabs cover token conversions, perpetual strategies, and basket investing. A Demo Wallet lets you explore the interface with simulated balances and fills.

## Swap

### Convert tokens

- Select supported SoDEX Spot and Wealth tokens and preview the amount you may receive.
- Review the order-book route and estimated fees. A conversion between two non-USDC assets routes through USDC.
- Use the Demo Wallet to try simulated conversions. Live conversion requires a supported market, an enabled environment, and a wallet signature.

### Manage funds and review activity

- Open Portfolio Details to see ValueChain EVM, Spot & Wealth, and Perps balances in donut or treemap views.
- Use Transfer for supported USDC moves between ValueChain EVM funding, Spot, and Perps. Funding routes through Spot when moving USDC between EVM and Perps.
- Browse recent demo conversions, five per page and up to 30 entries.
- The Cross-chain tab is marked Coming Soon.

## Perps

### Choose a strategy

- **Flash** targets short-term BTC and ETH opportunities. Each round lasts up to 15 minutes and can end early when it reaches its volume target. Advanced settings offer Maker or Taker entry in simulation. Manual exits use Taker execution.
- **Grid** supports BTC, ETH, and XAUt in simulation and places simulated Post-Only orders around a fixed anchor, with volatility-based spacing and Reduce-Only take profit. Choose a timed or continuous run and preview grid levels, costs, and margin.
- **Turtle** follows confirmed BTC and ETH breakouts using completed five-minute candles, Donchian channels, and ATR stops. Choose a two-, four-, or six-hour run or Continuous mode. SoSoValue news can tighten entry criteria or pause new entries.

### Monitor and control runs

- View active sessions, positions, remaining budgets, volume, and PnL. Pause, resume, stop entries, or close a position from the session controls.
- Open strategy details to review Grid orders and fills, or Turtle signals, stop prices, and relevant news.
- Filter completed sessions by strategy and sort by close time or net PnL.

The page runs simulations. Flash also offers a paper mode with live market data. The Grid and Turtle server runtimes require explicit enablement and authenticated workers for live execution.

## Wealth

### Explore and build strategies

- Browse preset baskets that cover crypto, tokenized stocks and funds, and SSI index tokens. Filter by category or risk level.
- Review asset weights and available seven-day historical price returns on strategy cards.
- Build a custom basket with up to 10 assets, including up to five Spot assets. Mix eligible Spot and Wealth tokens and set weights that total 100%.

### Invest and track

- Review the whole basket for a one-time purchase, including per-asset allocations and order minimums.
- Set up recurring purchases for eligible assets through SoDEX native DCA when live execution is enabled. Review the schedule and minimum amount before confirming. One recurring strategy can be active at a time.
- Use My Investments to review strategy allocations, invested amounts, and recurring plans. Cancel recurring plans from the same view.

## Wallet and Profile

- Connect a wallet or use the Demo Wallet to preview onboarding, trading permissions, and Builder Fee authorization.
- View portfolio allocations and holdings, hide balances, or filter out unsupported assets and holdings worth less than $1.
- Open Profile from the wallet menu to see Sonuki trading volume by Spot, Wealth, and Perps.

## SoDEX references

- [Perps trading](https://docs.sodex.com/for-developers/developers/trading/perp-trading)
- [Perps REST API](https://docs.sodex.com/for-developers/api-reference/trading-api/rest-v1/sodex-rest-perps-api)
- [Builder Codes](https://docs.sodex.com/for-developers/developers/trading/builder-codes-in-trading)
