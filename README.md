# Sol-RPC-Latency-Checker
A small Node.js tool that tests multiple Solana RPC endpoints for latency and reliability, and fetches the live SOL price from CoinGecko. Useful for evaluating infrastructure performance trading bots.  ✅ Built with @solana/web3.js  


Small demo that measures latency for a list of Solana RPC endpoints and fetches the current SOL price (CoinGecko). Useful as a quick health-check for arbitrage/trading readiness.

## How to run
1. Clone repo and `cd` into it.
2. Install deps:
```bash
npm install
