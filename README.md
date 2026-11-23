# Amin

Building MEEM Technologies: transparent, deterministic and auditable investment-technology software, with a focus on testable financial calculations.

I build tools where every number can be traced to a stated formula, a validated input and a passing test, with the financial assumptions written down rather than implied.

## Completed projects

### [Portfolio Risk X-Ray](https://github.com/AminQuantSystems/portfolio-risk-xray)

A Python tool that turns a CSV of portfolio positions into market values, portfolio weights, concentration flags and a weighted volatility exposure diagnostic.

- Strict input validation: bad financial data is rejected with a clear error, never silently dropped or repaired
- A separate finance library built with pandas, with a Streamlit interface on top
- 96 automated pytest tests, including hand-checkable golden fixtures, run on every push by GitHub Actions
- Documented limits: the exposure figure ignores correlation, and the README explains why it is not portfolio volatility, VaR or a risk contribution

### [Market Regime Monitor](https://github.com/AminQuantSystems/market-regime-monitor)

A deterministic market-state analytics application covering Direction, Momentum, realised Volatility, benchmark-relative Performance and categorical change monitoring.

- Python finance core, separate from a FastAPI adapter and React / TypeScript / Vite interface
- Explicit formulas, strict data validation, hand-checkable fixtures and deterministic reason codes
- Extensive automated finance, API and frontend tests, checked by GitHub Actions
- Containerised Azure demonstration architecture with verified-email access; hosted availability is separate from the repository's deployment evidence
- Analytical research software: no live market-data feed, investment recommendations, trading or portfolio construction

## How I work

- Deterministic calculations with stated units, conventions and thresholds
- Finance logic kept separate from presentation
- Small modules, each with its own tests
- Clear documentation of what a model does not claim

## Next: Portfolio Rebalancing Engine

The next planned major build is MEEM Technologies — Portfolio Rebalancing Engine: supplied holdings, cash, prices, target allocations and explicit rules would produce deterministic proposed actions and a projected portfolio state. It is not yet an implemented project on this GitHub account.

The longer-term direction is reusable portfolio, risk, market-data and investment-systems capabilities, with client-specific adapters around tested financial components. This is a development direction, not a claim that a complete institutional platform already exists.

## Tools

Python · pandas · pytest · FastAPI · React · TypeScript · Vite · Streamlit · Docker · Azure · GitHub Actions · Git

## Contact

Open to conversations about Python finance engineering, investment technology, portfolio and risk analytics, and systematic investing and markets technology.

LinkedIn: [linkedin.com/in/amin-khanyik](https://www.linkedin.com/in/amin-khanyik/)
