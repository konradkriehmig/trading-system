# Low-Latency Trading System

I deployed a high-performance VM as close as I can to the NYSE.

The physical proximity is what makes my ping faster than yours if you are not in US east.

I have high computing power in my VM that is useful for intensive backtesting (tbd)

## Latency Results (pings, trade algos to be implemented in another project)
- **Dublin → S&P data**: 81ms average
- **East US VM → S&P data**: 6ms average  
- **Improvement**: 92% latency reduction

## Setup
```bash
pip install -r requirements.txt
export ALPACA_API_KEY="your-key"
export ALPACA_SECRET_KEY="your-secret"
python dataFetcher.py
```
