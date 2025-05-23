# Uranium Auto Mining Bot

An automated bot for mining Uranium tokens from the [GetUranium](https://www.geturanium.io/) platform.

## Features

- Automatically mines Uranium tokens
- Multiple wallet support
- Referral system integration
- Random mining amounts
- Proxy support for IP rotation
- Detailed mining activity logs

## Register

- Link : https://www.geturanium.io?ref=0x03f11c992c6b93829bb09e354e3a5aeb5b7da5d8

## Prerequisites

- Node.js (v16+)
- npm or yarn

## Installation

1. Clone the repository:
```bash
git clone https://github.com/19seniman/uranium-miner.git
```

2. Navigate to the project directory:
```bash
cd uranium-miner
```

3. Install dependencies:
```bash
npm install
```

## Configuration

1. fill your address on .env :
```
nano .env

Format : 
WALLET_1=YOUR_WALLET_ADDRESS_1

WALLET_2=YOUR_WALLET_ADDRESS_2

# Add more wallets as needed...
```

2. fill your proxy on proxies.txt format:
```
Format :
ip:port
ip:port:username:password
```

## Usage

Run bot:
```bash
node index.js
```


## Disclaimer

This tool is for educational purposes only. Use at your own risk. The developers assume no liability and are not responsible for any misuse or damage caused by this program.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
