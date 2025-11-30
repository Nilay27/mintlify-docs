# AlphaEngine Docs

Documentation for AlphaEngine — a confidential, multichain liquidity engine built on Uniswap v4 with a CoFHE processor (Zama or Fhenix), EigenCompute operators, and Nexus dispatch.

## Structure

- `mint.json` – Mintlify config (navigation, branding, colors).
- `overview/` – high-level positioning and concepts.
- `architecture/` – system diagram, confidential liquidity flow, and strategy lifecycle.
- `compute/` – CoFHE processor primer and EigenCompute operator flow.
- `product/` – frontend and client responsibilities.
- `guides/` – quickstart and development workflows.
- `reference/` – deployments and other hard data.
- `README_ZAMA.md` – source material from the Zama build; flows are generalized in the docs as “CoFHE processor.”

## Local preview

```bash
# from repo root
npm install          # installs the Mintlify CLI locally
npm run dev          # or: npx mintlify@latest dev
# visit http://localhost:3000
```

Use `--port 3333` if 3000 is taken. Node 18+ recommended.
