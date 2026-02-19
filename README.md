# Low-Latency Trading System, what it does:

I deployed a high-performance VM as close as I can to the NYSE.

1. The physical proximity is what makes my ping faster than yours if you are not in US east.

2. I have high computing power in my VM that is useful for intensive backtesting later.

## Latency Results (pings)
- **My Laptop (Dublin) → S&P data**: 81ms average
- **My VM (East US VM) → S&P data**: 6ms average (92% latency reduction from my laptop)
- **Citadel → S&P data**: likely <1ms

My Laptop:

![asdf3](./assets/preview3.png)

My new fast Machine:
![asdf2](./assets/preview2.png)

<img width="611" height="391" alt="image" src="https://github.com/user-attachments/assets/24f838b1-94a6-41a9-9f16-a866d8d2dc70" />


## Infrastructure 
![Built in Azure](./assets/infra.png)

Can you be faster than me? --> if you want to try:

# Setup

1. go to Alpaca, create account, get API keys for paper trading from your dashboard
2. clone repo in VS code
3. in VS terminal bash: pip install -r requirements.txt
4. in VS terminal bash:
   $env:ALPACA_API_KEY="your-key-here"
   $env:ALPACA_SECRET_KEY="your-secret-here"
5. go

Easy :)

