🦅 Bercy MCP — Quad-Chain Payment Layer
The payment layer for all AI agents. x402 + AC2 on Algorand + Celo + Solana + Avalanche.

9 Tools
bercy_health — check all 4 chains live
bercy_rates — 95+ live FX corridors
bercy_convert — any currency pair
bercy_authorize — AC2 human approval
bercy_best_route — find fastest online chain (dynamic)
bercy_pay_celo — pay on Celo Mainnet (~1s)
bercy_pay_solana — pay on Solana Mainnet (~1s) + Jupiter
bercy_pay_avalanche — pay on Avalanche C-Chain (~2s)
bercy_pay_algorand — pay on Algorand Mainnet (~4s)
Chains
Chain	Status	Settlement	Protocols
Solana	✅ Live	~1 second	x402 + AC2 + Jupiter
Celo	✅ Live	~1 second	x402 + AC2
Avalanche	✅ Live	~2 seconds	x402 + AC2
Algorand	✅ Live	~4 seconds	x402 + AC2
Install
Add to .mcp.json in Claude Desktop.

How It Works
bercy_best_route → bercy_authorize → bercy_pay_<recommended>
bercy_best_route pings all chains live and always returns the fastest online chain automatically.

Built by @soheibabdou — Algeria 🇩🇿
