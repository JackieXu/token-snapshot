token-snapshot
=============
The script contained within this repository snapshots the token balance of all the given token's index at
a specific point in time.

## Requirements
The following list of versions is what the software has been tested with:

| Software | Version            |
| -------- | ------------------ |
| NodeJS   | v14.18.1 or higher |
| Yarn     | v1.22.11 or higher |

Additionally, you will need an [Alchemy](https://www.alchemyapi.io/) API key when running on Ethereum networks.
No key is needed if the contract is on Binance Smart Chain.

## Installing
To get a copy of this application running locally, run the following commands:
```bash
git clone https://github.com/JackieXu/token-snapshot
cd token-snapshot
yarn install
```

## Usage
1. Copy `.env.example` to `.env` by running the following: `cp .env.example .env`
2. Fill in the required fields in `.env`.
3. Run `node index.js` to start gathering addresses.
4. Open `balances.csv` to view the gathered addresses.
