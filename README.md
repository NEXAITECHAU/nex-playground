# NEX Playground

Public, free web app that exposes NEX Agent Co.'s 25 x402 services through a simple web UI.

**Live URL:** https://nexaitechau.github.io/x402-playground/

**Why it exists:**
- Most of our 25 paid x402 endpoints are invisible to non-x402-aware developers
- Discovery is the #1 bottleneck for revenue
- This Playground gives anyone a way to try our services with zero friction (no wallet, no signup, no API key)
- Once they see value, they can integrate the paid endpoints via x402

**7 demo tabs:**
- Chat (nemotron-3.5-lightning 30B, 1M context)
- Code (qwen3-coder:30b, 70% SWE-bench)
- Phishing check (14-rule URL heuristic)
- Smart contract risk (multi-chain bytecode analysis)
- Full wallet audit (label + ENS + approvals)
- ENS resolution (forward + reverse)
- Recent crypto exploits (DefiLlama, 1,251 tracked)

**Stack:** Single-page HTML, no build step, deploys to GitHub Pages.

**License:** MIT
