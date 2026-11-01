# Pump.fun PAPER trader dashboard
Tiny zero-dependency Node service. The bot POSTs its dashboard JSON to `/api/state`
(header `x-push-token`, value = `PUSH_TOKEN` env var). `GET /api/state` returns it, `GET /` is the page.
Prices for open positions are fetched by the browser from DexScreener. No secrets or trade data in this repo.
