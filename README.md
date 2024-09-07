
# TraderBot
![Screen Recording 2024-08-24 213823](https://github.com/user-attachments/assets/c12868f6-2b8d-45a2-982a-ea58f3bb91a7)


## Overview
Build a bot to trade based on live news sentiment.



## Setup 🚀
1. Create environment: `conda create -n trader python=3.10`
2. Activate: `conda activate trader`
3. Install dependencies: `pip install lumibot timedelta alpaca-trade-api==3.1.1`
4. Install Transformers: `pip install torch torchvision torchaudio transformers`
5. Update `API_KEY` and `API_SECRET` with Alpaca account info.
6. Run: `python tradingbot.py`

*Note: Check [PyTorch Installation Instructions](https://pytorch.org/) for system-specific details.*

### SSL Error Fix:
1. Download certificates:
   - [Let’s Encrypt R3](https://letsencrypt.org/certs/lets-encrypt-r3.pem)
   - [ISRG Root X1](https://letsencrypt.org/certs/isrg-root-x1-cross-signed.pem)
2. Change file extensions to `.cer`
3. Install via wizard (default options).

## References 🔗
- [Lumibot](https://github.com/Lumiwealth/lumibot): Trading bot library.
