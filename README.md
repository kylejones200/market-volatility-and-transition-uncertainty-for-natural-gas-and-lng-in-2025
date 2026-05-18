# Natural Gas and LNG Volatility Analysis

Published: yes
Medium: [https://medium.com/@kyle-t-jones/market-volatility-and-transition-uncertainty-for-natural-gas-and-lng-in-2025-51d972f4668a](https://medium.com/@kyle-t-jones/market-volatility-and-transition-uncertainty-for-natural-gas-and-lng-in-2025-51d972f4668a)


This project analyzes volatility and correlations in natural gas and LNG prices.

## Business context

The global gas and liquefied natural gas (LNG) landscape changing in response to market forces, policy shifts, and geopolitical tensions.

The [Biden administration's pause on new LNG export permits](https://www.reuters.com/business/energy/us-restricts-lng-exports-environmental-push-2024-01-10/) in 2024 over environmental concerns. The Trump administration is likely to look issue permits again for energy security. Europe still needs non-Russian gas and Asia's demand for LNG continues to grow. This means US Nat Gas supplies remain valuable and needed for global energy markets. However, the road ahead is still uncertain.

Asia continues to drive global LNG demand, but its approach is evolving. China has shifted toward a balanced strategy that leverages both spot market optimization and long-term contracts. Japan and South Korea are leading the push for lower-carbon LNG solutions, integrating [carbon-neutral LNG](https://www.spglobal.com/commodityinsights/en/market-insights/latest-news/natural-gas/041821-carbon-neutral-lng-finds-niche-in-japan-south-korea) into their energy mixes. Emerging markets like Vietnam and Thailand are rapidly building import infrastructure, signaling their commitment to natural gas as a key transitional fuel.

## Project Structure

```
.
├── README.md           # This file
├── main.py            # Main entry point
├── config.yaml        # Configuration file
├── requirements.txt   # Python dependencies
├── src/               # Core functions
│   ├── core.py        # Volatility analysis functions
│   └── plotting.py    # Tufte-style plotting utilities
├── tests/             # Unit tests
├── data/              # Data files
└── images/            # Generated plots and figures
```

## Configuration

Edit `config.yaml` to customize:
- Data source or synthetic generation
- Price columns to analyze
- Volatility window
- Correlation threshold
- Output settings

## Analysis Features

- Volatility Calculation: Rolling window volatility
- Correlation Analysis: Price relationships
- Trend Identification: Price movements over time
- Risk Assessment: Volatility patterns

## Caveats

- By default, generates synthetic price data.
- Volatility depends on window size.
- Correlations may vary over time periods.

## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).