# PharosTestnet-BOT
Pharos project, a Layer-1 blockchain fully compatible with the Ethereum Virtual Machine (EVM). It is designed to deliver high performance for Real-World Assets (RWA) and DeFi at an enterprise scale.
Register Here : [Pharos Testnet](https://testnet.pharosnetwork.xyz/experience?inviteCode=PNFXEcz1CWezuu3g)
- Connect New Wallet
- Connect X & Discord Account

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - `Choose 1`
  - Auto Run With Private Proxy - `Choose 2`
  - Auto Run Without Proxy - `Choose 3`
  - Auto Rotate Invalid Proxies - `y` or `n`
  - Auto Claim Daily Check-In
  - Auto Claim Faucet
  - Auto Make Transfer to Random Address
  - Multi Accounts

### Note: Other features will be update soon.

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/vonssy/PharosTestnet-BOT.git
   ```
   ```bash
   cd PharosTestnet-BOT
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

## Configuration

- **accounts.txt:** You will find the file `accounts.txt` inside the project directory. Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_private_key_1
    your_private_key_2
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

