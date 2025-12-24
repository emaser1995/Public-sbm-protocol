# Public Self-Balanced Market (PSBM) Protocol
### A Sovereign Asset Class resolving Shiller's "Trills" Paradox.

**Status:** Theoretical Framework v1.0  
**Author:** [Tuo Nome]

This repository contains the mathematical validation and the whitepaper for the **Public SBM Protocol**, a Layer-3 financial architecture designed to make GDP-linked Sovereign Bonds liquid and viable.

## 📄 The Whitepaper
[**Download the Full PDF Whitepaper**](./PSBM_Whitepaper.pdf)

The paper outlines how an **Asymmetric Automated Market Maker (AMM)** can act as a guaranteed counterparty for sovereign debt, eliminating the liquidity premium that caused previous attempts (like Shiller's Trills) to fail.

---

## 💻 Run the Simulation (Proof of Concept)
We believe in **"Verify, Don't Trust"**.
We have included a Python simulation script (`psbm_simulation.py`) to mathematically stress-test the protocol against a Bank Run.

**What the code demonstrates:**
The script simulates a scenario where **40% of the liquidity is withdrawn** in a panic event.
1.  **Price Crash:** The asymmetric burn engine drives the price down to protect the reserve ratio.
2.  **Yield Trap:** Since dividends are backed by Sovereign Assets/Taxes (Layer 1/2), the yield spikes from ~5% to >12%, creating a mathematical floor driven by arbitrage.

### How to run it:
If you have Python installed:
```bash
python psbm_simulation.py
