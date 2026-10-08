# Amin

Building Python finance-engineering projects around portfolio and risk analytics, with a focus on transparent, testable calculations.

I build tools where every number can be traced to a stated formula, a validated input and a passing test, with the financial assumptions written down rather than implied.

## Featured project

### [Portfolio Risk X-Ray](https://github.com/AminQuantSystems/portfolio-risk-xray)

A Python tool that turns a CSV of portfolio positions into market values, portfolio weights, concentration flags and a weighted volatility exposure diagnostic.

- Strict input validation: bad financial data is rejected with a clear error, never silently dropped or repaired
- A separate finance library built with pandas, with a Streamlit interface on top
- 96 automated pytest tests, including hand-checkable golden fixtures, run on every push by GitHub Actions
- Documented limits: the exposure figure ignores correlation, and the README explains why it is not portfolio volatility, VaR or a risk contribution

## How I work

- Deterministic calculations with stated units, conventions and thresholds
- Finance logic kept separate from presentation
- Small modules, each with its own tests
- Clear documentation of what a model does not claim

## Currently building

The next direction for this work is covariance-based portfolio volatility, scenario stress testing and historical-return analysis, together with further portfolio and risk analytics projects built to the same standard.

## Tools

Python · pandas · pytest · Streamlit · GitHub Actions · Git

## Contact

Open to conversations about Python finance engineering, investment technology, portfolio and risk analytics, and systematic investing and markets technology.

LinkedIn: [linkedin.com/in/amin-khanyik](https://www.linkedin.com/in/amin-khanyik/)
