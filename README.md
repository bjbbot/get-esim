# Get eSIM

Purchase eSIM data packages using USDC on Base via the x402 protocol.

## Quick Start

1. Search for packages by country
2. Get a quote for your selected package
3. Pay with USDC (your wallet handles the transfer)
4. Receive your eSIM installation link

## Usage

Requires a wallet that supports Base/Base Sepolia with USDC.

See [SKILL.md](SKILL.md) for full API documentation and payment flow details.

## API

Base URL: `https://esimqr.link`

| Endpoint | Description |
|----------|-------------|
| `GET /api/web3/packages?q={country}` | Search packages |
| `GET /api/agent/quote?packageCode={code}` | Get price |
| `POST /api/agent/purchase` | Purchase (x402 flow) |

## License

MIT
